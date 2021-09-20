# Noisy Stations

Below we summarize the best way to identify which stations are exceeding their monthly data allowances, how to identify which antenna might be causing problems, and suggestions on how you might be able to fix it. Regardless of whether a station is noisy, this type of optimization is useful to do to each station anyway. Radio interference introduces a lot of noise into the system that we should be working to reduce.

## **Addressing excessive noise**

Raw data from Lotek radio tags consist of long lists of time-stamped radio pulses. Four precisely-timed pulses are needed to identify a Lotek tag ID, but these pulses must be picked out from the surrounding noise environment. We consider noise to be any kind of radio pulse that is received by a station that was not produced by the intended target \(i.e., a radio tag\). Not only can this noise mask the pulses of real tags—preventing a receiver from picking it up—it can also produce signals that resemble real tags, resulting in a false positive detection. Excessive noise can be especially problematic for networked receivers that are using cellular or satellite connections. A single receiver experiencing excessive noise on a single antenna can easily produce over a GigaByte of data in a single month, resulting in $100’s in data charges.

**Noise Sources**

Noise can be present for a variety of reasons. Anthropogenic noise can be the most problematic when it comes to producing false positives as it is more likely for follow a repeated pattern, which is required for multiple false detections to occur in a row. In most cases we’ve experienced, noise tends to be problematic on only certain antennas, not all of them. Sometimes simply changing the direction of an antenna can solve the problem; however, it may also be necessary to disconnect problematic antennas until the issue can be resolved.  
Sometimes damaged hardware, such as cracked coaxial cables, or poor connections can also introduce noise into the system. In the case of a hardware issue, changing the antenna direction should have no effect on the level of noise detected.

## **Identifying excessive antenna noise using R**

Using the Motus R Package, summaries of raw radio pulses can be downloaded for each antenna and then compared to one another based on the number of pulses received each day. The threshold for the number of daily pulses depends how much data is considered ‘too much’, but generally most antennas record fewer than 1 million radio pulses a day.  

The following density plot shows a one-month period of data collected at Blackie Spit when nearly 2 GB of data were recorded over that time. As you can see, antenna 6 has been recording well over 1 million pulses a day, averaging around 4 million a day, whereas antenna 7 has a far more reasonable number of pulses. Based on this information, we can conclude that antenna 6 should be modified r removed to reduce the risk data overages.

![](.gitbook/assets/image%20%284%29.png)

  
You can produce your own plots like the one above using the code below. If you have not used the Motus R Package in the past we recommend reviewing Chapters 1-3 of the [Motus R Book](https://motus.org/MotusRBook/index.html) before proceeding.

This script uses the 'pulseCounts' table from the receiver database downloaded from the R package. To use this script, you must specify:

**Line 11:** Directory of where databases are stored on your computer

**Line 17:** Receiver metadata, including:

* Serial number of the receiver
* Name that you want printed in the plot title
* The size of the raw data files for the time period that you are reviewing
* The start date of the time period you are reviewing \(YYYY-MM-DD\)
* The end date of the time period you are reviewing \(YYYY-MM-DD\)

```text

# Required packages
library(motus)
library(tidyverse)
library(lubridate)

# Set the timezone to UTC
Sys.setenv(tz = "GMT")

# Select the directory where databases are stored on your computer
dir <- 'E:/Data/'

# Identify the receiver(s) you wish to plot
recvs.df <- tribble(
# Serial number       Name on plot    (MB)    Start date    End date
  ~recvID,            ~name,          ~size,   ~dtStart,     ~dtEnd,
  'CTT-F0C333DDFB45', 'Blackie Spit', 1789.18, "2021-07-01", "2021-08-01"
  ) %>%
  mutate(dtStart = as.Date(dtStart),
         dtEnd = as.Date(dtEnd),
         MB.daily = (size / as.integer(dtEnd-dtStart)) %>% round(digits = 3)) %>%
  as.data.frame()

# Run the code below and login using your Motus account credentials.
recvs.df %>% by(seq_len(nrow(recvs.df)),
  function(d) {
    message("Downloading data for ", d$recvID, " (", d$name, ")")
    
    sql <- tagme(projRecv = d$recvID, new = !file.exists(paste0(dir, d$recvID, '.motus')), update = F, forceMeta = F, dir = dir)
    
    message("Finished downloading")
    
    pulses.df <- sql %>% tbl('pulseCounts') %>% collect() %>% as_tibble() %>% 
      mutate(ts = as.POSIXct(hourBin*60*60, origin = '1970-01-01'))
    
    daily.pulses.df <- pulses.df %>% 
      mutate(day = ts %>% day,
             month = (ts %>% month),
             year = (ts %>% year)) %>%
      group_by(day, year, month, ant) %>%
      summarise(ts = min(ts),
                count = sum(count, na.rm = T))
    
    message("Found ", daily.pulses.df %>%
              filter(ts > d$dtStart, ts < d$dtEnd) %>% nrow(), " pulses.")
    
    message("Making the plot...")
    
    p <- daily.pulses.df %>%
      filter(ts > d$dtStart, ts < d$dtEnd) %>%
      ggplot(aes(count/1e+06))+
      geom_density()+
      facet_wrap(.~paste0("Antenna ", ant), ncol = 1, scales = "free_y")+
      labs(x = "Daily pulse count (millions)",
           y = "Count", 
           title = paste0(d$name, " (", d$recvID, "): ", d$MB.daily, " MB/day"))
    
    message("Done.")
    p   
    
  })
```

## How to fix a problematic antenna

Once a problem station/antenna has been identified we have a number of choices:

Quick Fixes:

1. Disconnect the station from the cell network entirely \(this is not ideal, but a quick fix\). See instructions on how to do so here -
2. Disconnect the problem antenna. Noisy antenna's generally may not be collecting the highest quality data to begin with so taking them offline is not a major impediment to the system. We are examining some data now to see just how many 'good' detections are detected on 'noisy' stations opposed to others and will report back in this thread. Obviously this will be a bigger deal for stations with active tags nearby, but for most passive listening stations, losing one noisy antenna likely won't be that big a deal.
3. Try installing band-pass-filters - [https://www.scannermaster.com/BPF\_VHF\_Band\_Pass\_Filter\_p/24-531041.htm](https://www.scannermaster.com/BPF_VHF_Band_Pass_Filter_p/24-531041.htm)

Harder Fixes:

1. Identify the source of the interference and attempt to aim the problem antenna away from that source.
2. Use antenna analyzer to verify the antenna still performs within a reasonable threshold \(link?\)
3. Use the process of elimination to identify whether it is a hardware problem. Replace all components of the problem antenna one at a time: USB cable; Radio Dongle; Coaxial Cable; Antenna.
4. Remove the antenna altogether.

