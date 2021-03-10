# Testing Receiver Antenna Ranges Using a Tag

_Please send any comments or additions to_ [_motus@birdscanada.org_](mailto:motus@birdscanada.org)

Estimated antenna detection ranges \(“[radiation patterns](https://en.wikipedia.org/wiki/Radiation_pattern)”\) are purely theoretical and based on ideal conditions so they do not actually reflect the true ranges or shapes of any real antenna \(Taylor et al 2017; Crewe et al. 2019\). The actual range of an antenna is not easy to calculate because it depends on several factors such as: transmitted signal \(by a tag\), antenna type and orientation, length and type of coaxial cable, receiver type, and environmental conditions. Best estimates of mean or max antenna ranges are based primarily on biological data when simultaneous detections are recorded by antennas from different stations.

Test tags have been used to try and get estimates of antenna ranges in specific situations \(Crewe et al. 2019\) and in drone tests \(Tremblay et al. 2017; Desrochers et al. 2018; Moore 2020\).

Test tag trials can take a lot of time and are not always necessary beyond simply confirming the station is working and an antenna capable of detecting tags nearby. The amount of information you require about antenna range will differ depending on the purpose of your station and the information found in trials may not be representative of actual antenna performance. It is also important to understand the physical limitations of antennas if they are surrounded by trees, or if there is a building or hill in the line of sight that may not always be apparent. Free tools such as [Google Earth](https://support.google.com/earth/answer/3064261?hl=en) and [HeyWhat’sThat](https://www.heywhatsthat.com/) can be used to find the ‘viewshed’, or line-of-site, of any given point and altitude.

Before you get started you should know that it is extremely difficult to emulate the performance of tags as they exist on living animals, the heights and flight directions of potential animals, and antennas, stations detecting living animals.

The following are suggested methods should you like to try and test the local range of a station and antennas.

## Tag Test Methods

### Supplies needed

* Lotek or CTT tag \(activated\)
* GPS with tracking on \(a phone can work\). Make sure units are set to LAT/LNG \(WGS84\)
* A stick or other non-conductive rod
* Dummy body: A small fruit \(grape or clementine\), tubed meat \(sausage, hot dog\), or frozen dead animal. _Differences between these objects are not well tested - take your pick._
* Water bottle
* Optional: helium balloon and lots of string
* Optional: a drone

### Making a dummy

* Take your activated tag and affix it to the dummy body using tape or string.
  * The purpose is to simulate the water content \(i.e., capacitance\)

    of an animal that is roosting such that the tag transmits a

    signal that resembles one coming from an actual bird. Keep in

    mind this is purely based on theory and is not an actual

    substitute for a real animal.
* Make sure the antenna hangs off the dummy in a similar orientation you’d expect it to be on your study species.
* This is required to stimulate tag performance for Lotek tags. Performance of CTT tags is not dependent on being affixed to an animal.

#### Ground simulation

To simulate an animal on or close to the ground, affix the dummy animal to a stick.

#### Flight Simulation

To simulate an animal in the air, affix the dummy animal to a helium balloon. _Note: balloons made from metalized mylar might influence signal transmission._

### Conducting the test

* With the tracking on, ensure your GPS has your location so that you can later download your track and correlate it with your tag detections. You may want to download a track ahead of time to make sure you know it works.
* While holding either the stick or the balloon, walk in concentric circles around the station of growing radius while trying to keep the tag at the same vertical position the whole time.
* Optionally, you can do this with a drone but don’t ask us how to fly it!
* It is also extremely difficult to know the position of the dummy within the [radiation pattern](https://en.wikipedia.org/wiki/Radiation_pattern) of the antenna in order to judge peak performance. [See description of different antenna types and radiation patterns here.](https://motus.org/antennas/#antennas)

![](/media/image9.png)

### Analyzing your results

* Download your GPS track and extract the timestamp and latitude/longitude for the entire test.
* Download your receiver data through R following instructions found in the [Motus R Book: Chapter 3](https://motus.org/MotusRBook/accessingData.html).
  * When using the ‘tagme’ function, make sure you enter the serial

    number of the receiver you’re testing as the ‘projRecv’

    argument, like so:

> _tagme\(projRecv = “SG-\#\#\#\#RPI3\#\#\#\#”, new = TRUE\)_

* You can now correlate your tag’s position with when detections

  occurred.

### Notes

You may be able to test two tags at different vertical positions simultaneously, but if they have the same burst interval there’s a good chance you’ll run into issues with aliased tags. I won’t go into too many details about them here, but essentially aliased tags are false detections that occur when two real tag detections overlap. To avoid this, just make sure you offset each tag activation such that there are at least 0.3 seconds between bursts.

## References

[Taylor, Philip, et al. "The Motus Wildlife Tracking System: a collaborative research network to enhance the understanding of wildlife movement." Avian Conservation and Ecology 12.1 \(2017\).](https://www.researchgate.net/publication/315716947_The_Motus_Wildlife_Tracking_System_a_collaborative_research_network_to_enhance_the_understanding_of_wildlife_movement)

[Crewe, Tara L., et al. "Detection range of songbirds using a stopover site by automated radio‐telemetry." Journal of Field Ornithology 90.2 \(2019\): 176-189.](https://onlinelibrary.wiley.com/doi/abs/10.1111/jofo.12291)

[Desrochers, André, et al. "Estimating wildlife tag location errors from a vhf receiver mounted on a drone." Drones 2.4 \(2018\): 44.](https://www.mdpi.com/2504-446X/2/4/44/pdf)

[Tremblay, Junior A., et al. "A low-cost technique for radio-tracking wildlife using a small standard unmanned aerial vehicle." Journal of Unmanned Vehicle Systems 5.3 \(2017\): 102-108.](https://www.nrcresearchpress.com/doi/pdf/10.1139/juvs-2016-0021)

[Moore, Jesse. "TRACKING MIGRATORY BIRDS: APPLYING A PASSIVE TRACKING TECHNIQUE USING DIRECTION OF ARRIVAL FROM VHF RADIO TAGS." \(2020\).](https://digitalcommons.uri.edu/cgi/viewcontent.cgi?article=2837&context=theses)
