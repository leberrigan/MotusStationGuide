


# Motus Station Guide

This guide has been created to help collaborators decide on how and where to install and maintain Motus stations.


[TOC]



# Introduction

There are several different ways a Motus station can be installed all of which depend on the location, purpose of the deployment, the infrastructure and equipment available.This guide will provide an overview of how different stations can be installed as well as some in-depth instructions on how to set up a variety of fixed, or free-standing towers with Yagi antennas and solar power. This booklet will not include a set of exhaustive instructions, but is intended as a guide that may need to be adapted to your project.


## Disclaimer and Health and Safety Tips

This guide is intended as a way to help individuals install their own Motus station for the purpose of collecting scientific tracking data that should be adapted to the needs and abilities of each individual. In addition, many installations include working at heights above 2 meters (6 feet). Follow instructions provided by suppliers and do not work without adequate knowledge or training. Individual projects will have to abide by local health and safe regulations, or those of thier host organization.

Motus Pro Tip - WEAR GLOVES!

Foot wear-

High-vis and hard hats -

Working from Heights -

Electrocution -


## What is a Motus Station?

A Motus station is an automated  radio telemetry station designed to listen to specific types of radio transmitters used to track wildlife. A large number of  TtThese stations, when  are what comprise the physical ground-based infrastructure of the Motus Wildlife Tracking System. A station consists of several parts: a radio receiver (computer) and peripherals such as antennas, cables, a mounting structure, and a power supply. Installing and maintaining a Motus station is no small task, but the rewards are great. This guide has been created to help collaborators build stations wherever they may be and should be adapted to the location and availability of equipment.


## Definitions

With all the terminology being thrown around with this technology, it can be hard to keep track of what’s what. We’re going to use our due diligence to ensure the information in this guide is accurate and concise, but you may run into inconsistencies elsewhere.

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Go to Appendix A for a terminology reference."). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Go to Appendix A for a terminology reference.](#heading=h.otprdi34k95o)


# Station Placement

	Not all stations are created equal. Some will primarily achieve local objectives, others are part of regional networks, and others strategically placed at migration, or movement hotspots to serve the collective needs of the entire network. At the end of the day, all stations collectively work together to make up the Motus network and provide data to far more projects than your own. Motus is the ultimate, hands-on, community science project.


## Site Selection

	Before deploying any stations, you need to know what the primary purpose of the station is. What works best for your region based on migratory flyways, topography and local infrastructure available, foraging locations, your goals, funding, the location of nearby stations.

Ideally, adjacent stations will complement one another; that is, they operate on similar frequencies and have antennas which point towards one another to provide detections of tagged animals as they pass between the stations. Multiple receivers can be employed to build a receiver ‘fence’ to detect any animals that may pass over a geographic area. Examples of these can be seen in the North-eastern US and along the North Sea of Europe. In Ontario, where many more stations are available, there is a grid of stations (or series of fences) to allow for better spatial resolution of movements. On study sites like Sable Island and Bon Portage Islands in Nova Scotia very small grids have been used to study local movements. In the end, you will need to decide what works best for your region based on migratory flyways, foraging locations, your goals, funding, and the location of nearby stations.


<table>
  <tr>
   <td>

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image1.png" width="" alt="alt_text" title="image_tooltip">

<p>
<a href="https://motus.org/wp-content/uploads/2020/02/receiver_fence_Panama.png">Receiver Fence \
(Panama Canal)</a>
   </td>
   <td>

<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image2.png" width="" alt="alt_text" title="image_tooltip">
<a href="https://motus.org/wp-content/uploads/2020/02/receiver_grid_Ontario.png">Receiver Grid \
(Ontario)</a>
   </td>
   <td>

<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image3.png" width="" alt="alt_text" title="image_tooltip">

<p>
<a href="https://motus.org/wp-content/uploads/2020/02/receiver_local_BonPortage.png">Local Array \
(Bon Portage Island)</a>
   </td>
  </tr>
</table>


	When selecting a site, it’s important to consider how the landscape features will affect the range of your antennas. Generally, higher stations have a greater range and detection probability of passing animals, but have a more limited probability of detecting local movements. In most instances, stationsd should be placed in the highest elevation possible within the area of interest, ensuring there is a clear line of sight in each direction you wish to point the antennas. It’s also important to ensure there aren’t any obstructions immediately behind the antennas (within a few meters), especially metal surfaces like roofing.

Node Networks: - introduction to nodes, how and where to use them. As CTT nodes, or small sensorgnome/receiver networks,


## It’s not magic, it’s physics. The importance of line or site, viewsheds,etc.


## Antenna Interference

	Antennas can receive interference if placed too close to metal objects or other antennas, or sources of electromagnetic noise (even aAir conditioners, generators, lawn mowers). Depending on frequency and location, radio interference from third-party broadcasters and cellular can also be problematic. Some online tools exist to locate licensed radio broadcasters by location ([click here for Canadian stations](https://tafl.jonathanmorgan.net/)).

One can conduct tests at a site prior to station setup - insert instructions on doing so.

	Yagi antennas should be vertically spaced according to their direction and frequency. Make sure you have ample spacing between your antennas and any sheet metal, such as roofing. The typical figure for minimum spacing and metal roofing is 1 full wavelength. Yagi antennas that point in the opposite direction (parallel) will interfere with each other if spaced too close together, essentially eliminating the directionality and severely impacting the detection range. Antennas that are parallel (180 degrees) should be at least ½, but best at a whole wavelength apart. Antennas that are perpendicular (90 degrees) should be at least ¼ wavelength apart.


<table>
  <tr>
   <td><strong>Antenna Type</strong>
   </td>
   <td><strong>Tags</strong>
   </td>
   <td><strong>Frequency</strong>
   </td>
   <td><strong>Wavelength</strong>
   </td>
  </tr>
  <tr>
   <td>9-element Yagi
   </td>
   <td>Lotek
   </td>
   <td>166.380 MHz
   </td>
   <td>1.80 meters
   </td>
  </tr>
  <tr>
   <td>9-element Yagi
   </td>
   <td>Lotek
   </td>
   <td>151.500 MHz
   </td>
   <td>1.98 meters
   </td>
  </tr>
  <tr>
   <td>9-element Yagi
   </td>
   <td>Lotek
   </td>
   <td>150.100 MHz
   </td>
   <td>2.00 meters
   </td>
  </tr>
  <tr>
   <td>9-element Yagi
   </td>
   <td>CTT
   </td>
   <td>434 MHz
   </td>
   <td>0.69 meters
   </td>
  </tr>
</table>



## Antenna Mounting Structure

	Motus stations have been built on just about anything – lighthouses, towers, trees, cars, drones, planes, ships, buoys, bamboo masts, and just about every type of building you can dream of.[ Click here for a list of example stations](https://motus.org/selection-guide/station-examples).

	The actual structure doesn’t necessarily matter as long as it’s strong and elevated enough to provide a clear line-of-sight, and the antennas are not mounted close to sheet metal or other antennas (see

<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Antenna Interference"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Antenna Interference](#heading=h.u7fm06fsrnjn) above). The easiest and often the perhaps cheapest method is often tto use a pre-existing building or structure upon which masts or antenna can be affixed to existing railings, or on the side of buildings where a DMX-style structure(link) can be mounted. Installation can be tricky, and every situation is different, but once it’s set up there shouldn’t won’t be much maintenance or worry.

	In remote locations where there aren’t any buildings to attach towers, one can use a tripod and mast like those manufactured by[ Wade Antenna](http://wadeantenna.com/), or other guyed or un-guyed self-standing tower design (link or picture). Pop-up These towers must be guyed (3 lines per 10-foot section) and anchored (1 anchor per guy or just 3 strong anchors). These structures are more sensitive to wind and ice than the DMX-style structures so regular maintenance will be necessary.

	We can’t stress enough the importance of excess supports in any setup situation. Use more and stronger guy wires than you think you need, more waterproofing, more wall mounts, bigger batteries, bigger solar panels, and strong gauge, galvanized or stainless steel materials (especially in marine environments). It will cost you more in the end per setup, but shortcuts will often cost you more in the long-term.

	The following list includes equipment commonly used across North America. For equipment used in other regions, please contact us.



*   Against wall of a building:[ DMX tower (36′)](http://wadeantenna.com/product/36-foot-dmx-bracketed-tower/)
*   Pre-existing Structures
*   Free-standing
*   Roof Mounts
*   Non-penetrating Roof Mounts
*   Wall Mounts
*   Non-penetrating roof mount:
    *   Stand:[ NPRM-2](http://wadeantenna.com/product/heavy-duty-non-penetrating-roof-mount/)
    *   [Masting](http://wadeantenna.com/product/masting/)
*   Free-standing:
    *   Tripod:[ TRM-10L](http://wadeantenna.com/product/10-foot-tripod/)
    *   Telescopic Mast (40-foot):[ 40A](http://wadeantenna.com/product/1499/)
    *   Also requires: guy lines and anchors when mounting multiple antennas

	With all these mounting methods in mind, we recommend you contact your local supplier for[ Wade Antenna](http://wadeantenna.com/) to find the best solution for your location.


## **Insert instructions? - **


# Receivers

The Motus Network mostly consists of stationary automated radio telemetry stations receivers which continuously record incoming radio pulses. Mobile stations receivers also exist, either affixed to a moving vehicle, boat,  or in a backpack on foot. Other receivers are used for manual tracking so that wildlife can be located in and observed in-person for more precise location data.


## Automated Telemetry Receivers

There are three types of receivers compatible with Motus that can be purchased, or built yourself in some cases: Lotek Wireles Inc (SRX600, 800 and D-series receivers), CTT Sensorstation and Nodes, and the open-source SensorGnome.

	Sensorgnomes can be purchased from[ Compudata](https://compudata.ca/sensorgnome/) or[ RFS Scientific](https://www.rfsscientific.com/) or built with the[ following instructions](https://archived.sensorgnome.org/How_do_I_build_a_SensorGnome/). Note these instructions are very outdated and require revision. New instructions will be posted in the near future.


<table>
  <tr>
   <td>
   </td>
   <td>
<strong><a href="https://sensorgnome.org">SensorGnome</a></strong>
   </td>
   <td><strong><a href="https://store.celltracktech.com/collections/wildlife-telemetry-products/products/ctt-sensorstation-for-sensorgnome-v-2-0">CTT SensorStation</a></strong>
   </td>
   <td>
<strong><a href="https://www.lotek.com/products/srx800/">Lotek SRX-800</a></strong>
   </td>
  </tr>
  <tr>
   <td><strong>Compatible with Lotek Tags</strong>
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><strong>Compatible with CTT Tags</strong>
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td><strong>Base Price</strong>
   </td>
   <td>$625 USD<sup>3</sup>
   </td>
   <td>$589 USD board only<sup>1</sup>
   </td>
   <td>[Contact Lotek]
   </td>
  </tr>
  <tr>
   <td><strong>Accessories</strong>
   </td>
   <td>DC power converter (for solar installations): $45-75 USD
   </td>
   <td><a href="https://celltracktech.com/price-list/">Price list</a>
<p>
Waterproof case: $45 USD
<p>
Wi-Fi Module: $30 USD
<p>
Cellular Module: $50 USD
<p>
Power supply (for AC installations): $25 USD
<p>
Bulkheads (1 required per antenna): $10/each USD
<p>
Health Reports Data Plan: $5 USD/Month
<p>
Automatic Upload Data Plan: $5 USD/Month Base + Data
   </td>
   <td>[Contact Lotek]
   </td>
  </tr>
  <tr>
   <td><strong>Price per Lotek-compatible antenna dongle</strong>
   </td>
   <td>$200 USD
   </td>
   <td>$200 USD
   </td>
   <td>$0 (included)
   </td>
  </tr>
  <tr>
   <td><strong>Price per CTT-compatible antenna dongle</strong>
   </td>
   <td>$100 USD
   </td>
   <td>$0 (included)
   </td>
   <td>Not compatible
   </td>
  </tr>
  <tr>
   <td><strong>Remote data download and diagnostics? (Requires internet)</strong>
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
   <td>Yes
   </td>
  </tr>
  <tr>
   <td><strong>Internet connectivity?</strong>
   </td>
   <td>Ethernet and Wi-Fi; cellular modem can be installed separately
   </td>
   <td>Cellular<sup>2</sup> OR Wi-Fi; Ethernet
   </td>
   <td>Cellular (modem purchased separately)
   </td>
  </tr>
  <tr>
   <td><strong>License</strong>
   </td>
   <td>Open-source hardware and software
   </td>
   <td>Open-source hardware and software
   </td>
   <td>Proprietary
   </td>
  </tr>
  <tr>
   <td><strong>Used for manual tracking</strong>
   </td>
   <td>Possible with added battery pack, but not well tested.
   </td>
   <td>No, but see CTT Locator
   </td>
   <td>Most models can be used for manual tracking.
   </td>
  </tr>
  <tr>
   <td><strong>Build-your-own</strong>
   </td>
   <td>Yes<sup>3</sup>
   </td>
   <td>No
   </td>
   <td>No
   </td>
  </tr>
  <tr>
   <td><strong>For Price</strong>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


<sup>1</sup> Price does not include cost of: Wi-Fi module; cellular module; data plans; case; power supply; bulkheads (1 required per antenna); or testing time.

<sup>2</sup> CTT charges $5/month base plus data costs for cellular data plans and an additional $5/month for station health reports. Contact CTT for more details.

<sup>3</sup> Cost for self-built SensorGnomes is estimated to be ~$150 USD without dongles, but prices may vary. Instructions on building SensorGnomes can be found[ here](https://archived.sensorgnome.org/How_do_I_build_a_SensorGnome/), but note these are very outdated and require revision. New instructions will be posted in the near future. We do not recomend collaborators build their own SensorGnome without prior experience.


## Manual Telemetry Receivers

For manual telemetry, we need a portable receiver that can decode tag IDs in real time.


##


# Antennas, Cables, and Dongles


## How to Select an Antenna

It is very important you select the right antenna for the purpose of the station and the type of tags you intend to detect. Antennas are optimized for reception on a particular radio frequency. Since there are multiple tag frequencies, each tag type requires its own antenna; currnetly an antenna optimized to detect Lotek tags on 166.380 Mhz  will not detect CTT tags on 434 Mhz, and vice versa. Wherever possible we recommend installing “dual-mode” stations outfitted with antennas and a receiver that can detect tags both Lotek and CTT tags. A dual-frequency antenna is under development, but for the time being, dual-mode stations (those that can listen for more than one frequency, both Lotek and CTT tags) must have two different types of antenna in place.

An antenna is a device used to send or receive radio signals, i.e., electromagnetic radiation. This radiation induces a voltage in conductive materials which will vary in magnitude based on the physical dimensions and orientation of the material. The induced voltage oscillates at the same frequency as the electromagnetic radiation and the amount of voltage induced is proportional to the strength of the radiation.  Antennas used in this network are built (“tuned”) with high precision such that the induced voltage is most intense when exposed to a narrow range of frequencies. Antennas can also be shaped to select for radiation from specific directions and orientations.

<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.gif). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.gif "image_tooltip")


Each antenna has a theoretical radiation pattern which represents its range in 3D space. We use the radiation pattern to predict the distance and direction we can receive signals from radio transmitters. Omnidirectional (‘omni’) antennas, as the name suggests, have a uniform radiation pattern that is emitted perpendicular to its axis. The thin wire attached to Lotek and CTT tags is a type of omni antenna. When used on a receiver, omni antennas provide presence/absence information, typically within a short range. This makes them ideal for fine scale studies and are indeed used with CTT SensorNodes to create a high-resolution grid.



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")


<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.gif). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.gif "image_tooltip")


A torus, representing the radiation pattern of an omnidirectional antenna (left; [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0), source: [Wikipedia](https://commons.wikimedia.org/wiki/File:Simple_Torus.svg)). Cross-sectional view of a half-wave omni-directional antenna (right; public domain, source: Wikipedia).

Yagi-Uda (‘Yagi’) antennas are a type of directional antenna that are the most commonly used antenna in the Motus network. Their radiation pattern is directed into a beam which varies in length and width based on the number of ‘directing elements’ with a greater number of elements resulting in a longer, narrower beam. A 9-element Yagi antenna, for instance, can theoretically provide tag detections from 15 km away at 166.380 MHz, but this will vary widely in reality, based on the landscape and atmospheric conditions. Yagi antennas are favorable for most applications since they can be used to create receiver ‘fences’ or ‘grids’ with fewer stations than an omni antennas could. In addition, multiple Yagi antennas on a single station can be used to infer flight direction based on the timing of detection across each antenna.

	A variety of antenna options exist for VHF/UHF telemetry. To date, collaborators have used 3, 5, 6, and 9-element Yagi directional antennas, and omni-directional antennas. Generally the greater the number of elements, the longer the detection range and more narrow the detection beam. The fewer the elements, the shorter the detection range, but the broader the detection beam. Omni-directional antennas are best suited for determining species presence-absence patterns (e.g. seabirds at a colony), or for detecting birds in close proximity to stations (within a few hundred metres), not suited for providing directional information (e.g. departure directions of songbirds from a stopover site).

	Large Yagi antennas are useful for making receiver fences and grids since they can be spaced as far as 30 km apart with antennas pointing towards each other to capture animals passing in between. Mid-sized Yagi antennas provide a compromise between distance and “field of view”, or width of the detection beam. Small Yagi antennas are typically used for manual tracking, or for monitoring animals within a small study area.[ CTT Nodes](https://celltracktech.com/products/tag-system/ctt-node/) have small omni antennas with a line-of-sight (LOS) range of around 1.4 km which if distributed in a grid can provide highly accurate location estimates. 	See array design above.


## Ordering Antennas

When ordering antennas and cables, it is important to ensure:



1. Connectors between the coaxial cable, antennas, and receiver are compatible.
2. The impedance rating of all cables, connectors, and dongles are the same (50 Ohms).
3. Cable type is suitable for the length needed.
4. Get recommended equipment if inexperienced with the technology (highlighted in green).

Select an item from the list below to learn more:



*   [Antennas](https://motus.org/antennas/#antennas)
*   [Coaxial Cables](https://motus.org/antennas/#cables)
*   [Radio Dongles](https://motus.org/antennas/#dongles)
*   [Connectors](https://motus.org/antennas/#connectors)


## Antenna Anatomy


### Yagi-uda

This antenna, usually referred to as simply “Yagi” or more generally a directional antenna.


##

<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")



## Antenna Types

A variety of antenna options exist for VHF telemetry. To date, users have used 3, 5, 6, and 9-element Yagi directional antennas, and single-pole omni-directional antennas. The 9-element Yagis have a long, narrow detection range, whereas 3, 5, or 6-element Yagis have gradually shorter and wider detection ranges. Omni-directional antennas are best suited for determining species presence-absence patterns (e.g. seabirds at a colony), or for detecting birds in close proximity to stations (within a few hundred metres), but not for providing directional information (e.g. departure directions of songbirds from a stopover site).

When ordering antennas, it’s important to know what frequency you need it to be tuned to. For detecting Lotek tags, antennas must be tuned to 150.1 MHz (Europe), 151.5 MHz (Australia), or 166.380 MHz (Western Hemisphere), depending on the region. For detecting CTT tags, antennas must be tuned to 434 MHz.

Antennas can be purchased from the following suppliers:



*   [Laird- through Hutton in Canada Economy 2-way in US](https://www.arcantenna.com/plc1669-laird-yagi-heavy-duty-9-element-antenna-for-166-174-mhz-with-uhf-female-connector-track-migratory-birds.html)
*   <span style="text-decoration:underline;">Wade Antenna \
[Maple Leaf Communications](http://www.mapleleafcom.com/)</span>
*   [Cellular Tracking Technologies](https://celltracktech.com/)
*   [Digikey](http://www.mapleleafcom.com/)
*   [Lotek Wireless Inc.](https://celltracktech.com/)

Use the table below to help select your antenna:


<table>
  <tr>
   <td><strong>Antenna type</strong>
   </td>
   <td><strong>Typical price (USD)</strong>
   </td>
   <td><strong>Impedence</strong>
   </td>
   <td><strong>Theoretical range</strong>
   </td>
   <td>
<strong>Veiw</strong>
   </td>
  </tr>
  <tr>
   <td><strong>3-element Yagi</strong>
   </td>
   <td>$$$
   </td>
   <td>50 Ohms
   </td>
   <td>~5 km
   </td>
   <td>Wide directional
   </td>
  </tr>
  <tr>
   <td><strong>5-element Yagi</strong>
   </td>
   <td>$$$
   </td>
   <td>50 Ohms
   </td>
   <td>~8 km
   </td>
   <td>Directional
   </td>
  </tr>
  <tr>
   <td><strong>6-element Yagi</strong>
   </td>
   <td>$$$
   </td>
   <td>50 Ohms
   </td>
   <td>~10 km
   </td>
   <td>Directional
   </td>
  </tr>
  <tr>
   <td><strong>9-element Yagi</strong>
   </td>
   <td>$$$
   </td>
   <td>50 Ohms
   </td>
   <td>~15 km
   </td>
   <td>Narrow directional
   </td>
  </tr>
  <tr>
   <td><strong>Omnidirectional</strong>
   </td>
   <td>$$$
   </td>
   <td>50 Ohms
   </td>
   <td>~1 km
   </td>
   <td>Omnidirectional
   </td>
  </tr>
  <tr>
   <td colspan="4" >Items listed in green are recommended.
   </td>
   <td>
   </td>
  </tr>
</table>



## Coax Cables


<table>
  <tr>
   <td><strong>Cable type</strong>
   </td>
   <td><strong>Typical price (USD)</strong>
   </td>
   <td><strong>Impedance</strong>
   </td>
   <td><strong>Max attenuation</strong>
<p>
<strong>(dB/100 ft)</strong>
   </td>
   <td>
<strong>Suggested length</strong>
   </td>
  </tr>
  <tr>
   <td><strong><a href="https://www.pasternack.com/flexible-0.195-rg58-50-ohm-coax-cable-pvc-jacket-rg58c-u-p.aspx">RG-58</a></strong>
   </td>
   <td>&lt; 100 ft. @ $0.83/ft.
   </td>
   <td>53.5 Ohms
   </td>
   <td>4.4 @ 100 MHz
<p>
6.0 @ 200 MHz
<p>
8.5 @ 400 MHz
   </td>
   <td>&lt; 50 ft./15 m
   </td>
  </tr>
  <tr>
   <td><strong><a href="https://www.pasternack.com/flexible-0.405-rg213-50-ohm-coax-cable-pvc-jacket-rg213-u-p.aspx">RG-213</a></strong>
   </td>
   <td>&lt; 100 ft. @ $1.79/ft.
   </td>
   <td>50 Ohms
   </td>
   <td>2.3 @ 100 MHz
<p>
4.8 @ 400 MHz
   </td>
   <td>&lt; 100 ft./30 m
   </td>
  </tr>
  <tr>
   <td>TWS/BMR/
<p>
<strong><a href="https://www.pasternack.com/50-ohm-low-loss-flexible-lmr400-pe-jacket-double-shielded-black-lmr-400-P.aspx">LMR-400</a></strong>
   </td>
   <td>$1.20/ft.
   </td>
   <td>50 Ohm
   </td>
   <td>1.5 @ 150 MHz
<p>
2.7 @ 450 MHz
   </td>
   <td>Any length
   </td>
  </tr>
</table>


A helpful guide on coaxial cables can be found on the[ Wilson Amplifiers website](https://www.wilsonamplifiers.com/blog/understanding-coaxial-cables-the-complete-guide/)

A catalogue of cables and their specifications can be found on[ Allied Wire & Cable](https://www.awcwire.com/producttoc.aspx?id=coaxial-cable).



*   **RG58** – basic communications cable that typically comes with a BNC connector. Best used for lengths less than 50′. The least expensive option.
*   **RG213** – higher grade cable that can be used at length of up to 100′ with low signal loss. Custom cable ends depending on distributor/manufaturer. Moderate price.
*   **TWS/LMR-400** – similar to the RG-213, but higher quality (stronger weather/sun resistance) coating. Best for longer-term installations and long cable length. Most expensive. Manufacture can suggest which cable is best for your needs – LMR is generally more affordable.
*   **BMR-400** - available from Maple Leaf Communications, this cable has slightly less plastic insulation, making it much more flexible and easier to work with than LMR-400, while offering similar attenuation.

		Motus Pro Tip - The heavier guage cables can be buly to work with and awkward to connect inside the receiver. Short jumper cables with smaller guage can be used to help work in tight spaces. Insert picture and example from Maple Leaf. However, this does increase the number of connections which may result in a slight decrease in signal strength (see connectors below).


## Radio Dongles

	Radio dongles, also known as Software Defined Radios (SDRs), are used to convert the analog signal received by the antennas into a digital signal that can be interpreted by the SensorGnome or SensorStation. Note that Lotek receivers have a built-in converter and do not require these for station operation. Note that SensorStations only need an SDR for antennas tuned for Lotek tags (anything that isn’t 434 MHz).

	While there are dozens of available SDR’s on the market, only four models are compatible with SensorGnomes and SensorStations. Most commonly used are the **FUNcube Pro Plus** which have the smallest signal-to-noise ratio (_<span style="text-decoration:underline;">SNR</span>_), _<span style="text-decoration:underline;">noise figure</span>_, and _<span style="text-decoration:underline;">DC voltage spike</span>_ (poor reception at nominal frequency), and power rating. However, FUNcube dongles are the most expensive, costing ~$200 USD, compared to $35 USD for the **RTL-SDR**. Despite the high price, we currently recommend FunCubes as the other SDR’s have not been properly tested or optimized for use. See the table below for more information:


<table>
  <tr>
   <td><strong>Receiver</strong>
   </td>
   <td><strong>Price (USD)</strong>
   </td>
   <td><strong>Power in use</strong>
   </td>
   <td><strong>Power while idle</strong>
   </td>
   <td><strong>Reliability</strong>
   </td>
   <td><strong>Typical noise figure</strong>
   </td>
  </tr>
  <tr>
   <td><strong>FUNcube Pro Plus</strong>
   </td>
   <td>$225
   </td>
   <td>0.8 W (48 kHz)
   </td>
   <td>0.8 W (48 kHz)
   </td>
   <td>Very reliable
   </td>
   <td>3.5 dB @ 145 MHz
   </td>
  </tr>
  <tr>
   <td><strong>RTL-SDR blog V3</strong>
   </td>
   <td>$22
   </td>
   <td>1.5 W
   </td>
   <td>0.7 W
   </td>
   <td>Unknown
   </td>
   <td>~5 dB @ 144.3 MHz
   </td>
  </tr>
  <tr>
   <td><strong>NESDR SMArt v4</strong>
   </td>
   <td>$24
   </td>
   <td>1.54 W
   </td>
   <td>&lt;0.25 W
   </td>
   <td>Unknown
   </td>
   <td>Unknown
   </td>
  </tr>
  <tr>
   <td><strong>NESDR SMArtee</strong>
   </td>
   <td>$26
   </td>
   <td>1.43 W
   </td>
   <td>Unknown
   </td>
   <td>Unknown
   </td>
   <td>Unknown
   </td>
  </tr>
  <tr>
   <td><strong>NESDR Smart XTR</strong>
   </td>
   <td>$38
   </td>
   <td>1 W
   </td>
   <td>0.6 W
   </td>
   <td>Unknown
   </td>
   <td>Unknown
   </td>
  </tr>
  <tr>
   <td><strong>CTT*</strong>
   </td>
   <td>$100
   </td>
   <td>&lt;0.25 W
   </td>
   <td>&lt;0.25 W
   </td>
   <td>Unknown
   </td>
   <td>Unknown
   </td>
  </tr>
</table>


* CTT dongles listen to 434 MHz and are only used to make Sensorgnomes compatible with CTT tags.

Items listed in green are recommended.






## Connectors

	There are several types of connectors that are used with radio antennas and coaxial cables, but not all perform equally. For instance, certain connectors are better at preventing water and dust ingress. For this reason, it’s important to know what kind of connectors your antennas have when being purchased, and which are most suitable for a Motus station. There are four connector types commonly found in Motus station setups: _UHF_ (_PL-259_);_ N-type_; _BNC_; and _SMA_.

	Most 9-element Yagis and omni-directional antennas tend to come with a female UHF (Laird) or N-type connector (Maple Leaf), but this should be verified prior to purchase. Three and 5-element Yagis usually come with a male BNC connector and so they can be connected to a Lotek SRX receiver directly, or to a FUNcube with female BNC to male SMA adapter.

	It’s generally recommended to keep the number of connections to a minimum to reduce the amount of signal loss and noise.

	The following table outlines where we typically see these connectors. Dongles are the analog-to-digital converters that are part of the Sensorgnome (typically we use FUNcube dongles, or FCD).


<table>
  <tr>
   <td rowspan="2" ><strong>Connector</strong>
   </td>
   <td colspan="3" ><strong>Device</strong>
   </td>
   <td rowspan="2" ><strong>Water resistance</strong>
   </td>
  </tr>
  <tr>
   <td><em>Antenna</em>
   </td>
   <td><em>Cables	</em>
   </td>
   <td><em>Radio Dongles</em>
   </td>
  </tr>
  <tr>
   <td><strong>UHF	</strong>
   </td>
   <td>Common
   </td>
   <td>Common
   </td>
   <td>Never
   </td>
   <td>Good
   </td>
  </tr>
  <tr>
   <td><strong>N-type	</strong>
   </td>
   <td>Common
   </td>
   <td>Common
   </td>
   <td>Never
   </td>
   <td>Best
   </td>
  </tr>
  <tr>
   <td><strong>BNC</strong>
   </td>
   <td>Some Lotek
   </td>
   <td>Common
   </td>
   <td>Never
   </td>
   <td>Poor
   </td>
  </tr>
  <tr>
   <td><strong>SMA</strong>
   </td>
   <td>Never
   </td>
   <td>Some adapter cables GPS cables
   </td>
   <td>Always
   </td>
   <td>Good
   </td>
  </tr>
</table>


Items listed in green are recommended.

The following are some common uses of these connectors:



1. Coax cable with male BNC connector at one end and male UHF connector at the other end (for Lotek receivers or Sensorgnomes with female BNC to male SMA adapter).
2. Coax cable with a male BNC connector at both ends with a BNC female to UHF male adapter (Lotek receivers or Sensorgnomes with female BNC to male SMA adapter).
3. Coax cable with custom female UHF connector at the antenna end and a male SMA connector at the FUNcube end. (Option with fewest adapters and therefore less signal loss, but may be more expensive due to custom ends). Sensorgnome only.

Motus Pro Tip - every connection, every adapter, may result in lowering the sensitivity of station to detect tags. Make every effort to minimize the number of connections/adapters between the antenna and the receiver.


# Power

You can’t have a reliable station without a reliable power source. For this reason, it’s best to ensure more than an ample supply is available.


## Power Sources

Receivers can be powered by either AC or DC. AC power supplied by mains should be used whenever possible as it is generally a more reliable and cheaper power supply than DC. DC supplies usually come in the form of Deep Cycle batteries and require regular charging via solar or another method to maintain power. Also keep in mind that since DC typically requires a solar panel and battery it is a more attractive target for thieves.


### AC Supply

If using mains AC power from a typical wall outlet, ensure you use a good quality power adaptor that is rated for the mains power of that region (e.g.: North America is 120 Vrms @ 60 Hz; South America is [highly variable](https://www.tripsavvy.com/south-america-outlets-and-adapters-1637155), 115-230 Vrms @ 50 or 60 Hz). A good quality adaptor can tolerate this variation in mains voltage which makes them more versatile for projects across multiple countries. A poor quality adaptor will produce an unstable voltage which can damage a receiver or not produce enough power to keep it operational. You may also want to connect your station through a proper surge protector.

The type of adaptor required will depend on the type of receiver being used. For CTT SensorStations and Lotek SRX receivers, these power supplies are usually included with the receiver. SensorGnomes will also be shipped with an AC power supply when ordered through Compudata or RFS Scientific.

If you do not have a power adaptor for your SensorGnome receiver, you can use a standard USB power supply for your phone (“fast charger” or minimum of 2.5 Amps) with a USB cable. For CTT or Lotek receivers, contact your supplier to purchase an adaptor.

If mains power is unreliable and 24/7 coverage is needed, then you may wish wish to connect your station through a battery powered backup power supply.


### DC Supply

Powering electronics directly from DC is more complicated since there is no single setup for all stations. Instead, the type and amount of power required will depend largely on region and available resources. In order for a station to be compatible with a DC power supply, it must have a method for converting the voltage of a battery - usually 12 volts - to something the receiver can handle, which ranges from 5 to 18 volts, depending on the model.



*   CTT SensorStations have built-in voltage converters, allowing them to accept a direct connection to the battery; however, in practice NEVER connect your receiver directly to the battery without a

<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "low-voltage cutoff"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[low-voltage cutoff](#heading=h.wkgzusibnpq8) to protect your battery.
*   SensorGnomes, require a DC buck converter to lower the voltage down to 5 volts. Buck converters are only provided in SensorGnomes if requested when purchasing from Compudata or RFS Scientific.
*   Contact Lotek or see your receivers user manual for more information on SRX series receivers.


### Battery


#### Type

	**Lead-acid batteries** are based on very old technology, but still provide the cheapest, non-volatile power storage for electronics. Lithium-based batteries offer the highest energy density of any commercially available battery, yet they are far more expensive relative to the power they store. In addition, Lithium-based batteries are typically far more volatile, risking chemical spills and fire if they are charged/discharged too quickly, if their temperature is too high or if they are punctured. For these reasons we do not recommend Lithium-based batteries unless space and weight is very limited. Since lithium-based batteries are used so rarely in the Motus network, they will not be discussed further here.

Most people refer to 12-volt lead-acid batteries as “car batteries,” but in this instance you might get the wrong type if that’s what you ask for. This is because car batteries are not designed to be discharged over long periods of time and require constant top-ups, such as from a car’s alternator. In a Motus station, batteries must be able to go down to voltages as low as 10-11 volts each night without losing much capacity - this would ruin the typical car battery in no time!

	This is why we use **deep-cycle batteries** which allow a deep discharge during each charging cycle. Most deep-cycle batteries that are readily available are marine grade (a.k.a.: “marine battery”) which are designed around offering high cranking amps to start up large boat motors, but this is not anything we need in a radio station. Nonetheless, in remote locations with nothing else available, a marine battery will do. While more expensive, specialize solar deep-cycle batteries are also available that are designed provide small amounts of power continuously and varying degress of recharging.

	You may also notice there are **flooded **and **sealed lead-acid** (SLA) batteries that exist. This refers to whether the internal chemistry can offgas externally. Flooded lead-acid batteries are well known for producing highly flammable hydrogen gas and can be extremely hazardous if not stored in a well-ventilated area. We usually store batteries in a closed tupperware bin which increases the potential of this hazard which is why we recommend **SLA batteries.** Even so, batteries should be handled with care so as to not puncture the battery casing, potentially allowing the slow release of hydrogen gas over time.

We recommend the use of Trojan batteries (minimum XX amp/hour), specifically XXX.


#### Capacity

Battery capacity is recorded in Amp-hours (Ah) or Watt-hours (Wh) which is a measurement of current or wattage consumed multiplied by the amount of time current flows. This is helpful because we can easily calculate the amount of Amp-hours we expect our receiver to consume by reviewing the _

<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "power consumption table"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[power consumption table](#heading=h.mv2i8hd0o7fr)_ or by measuring the current of a connected receiver using a voltmeter. Put simply, a SensorGnome which consumes 0.5 A of power at ~12 volts can theoretically run off a 50 Ah battery for 100 hours (50 Ah / 0.5 A = 100 h). Keep in mind that you won’t ever use the full capacity of a battery since it should not be discharged below 10.5 volts (see

<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Undervoltage Protection"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Undervoltage Protection](#heading=h.wkgzusibnpq8)). In addition, the capacity will slowly decrease over time with each discharge of the battery, so ensure you add an extra 10-15% of capacity to account for this drop over time. Batteries vary in performance at different temperatures as well and average a shorter lifespan in warmer climates.

When shopping for batteries, we recommend a 50 Ah battery for day lengths greater than 12 hours and a 75 Ah for day lengths under 12 hours.


#### Undervoltage Protection

	When using any type of battery to power a station, it is recommended to _always _use undervoltage protection so you do not ruin your battery. While your station may function without one, it greatly reduces battery life and will eventually result in the battery not holding any charge. If using a solar panel to charge the battery, you will require a

<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "charge controller with low voltage cutoff"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[charge controller with low voltage cutoff](#heading=h.6chq1w9ghov0). Without a charge controller, you will need to buy a low voltage cutoff, also known as an undervoltage protection module. These are readily available online, like on [Amazon](https://www.amazon.ca/Charging-Controller-Protection-Undervoltage-Automatic/dp/B07B49T4DQ/ref=pd_lpo_60_t_0/133-0210339-1957978?_encoding=UTF8&pd_rd_i=B07B49T4DQ&pd_rd_r=eee44559-b6ec-47a1-b70d-098543031793&pd_rd_w=H8ZTa&pd_rd_wg=FZYsE&pf_rd_p=256a14b6-93bc-4bcd-9f68-aea60d2878b9&pf_rd_r=EX2M9R1V9M0B43R022ZX&psc=1&refRID=EX2M9R1V9M0B43R022ZX).

We recommend Sunsaver charge controllers with low-voltage cut-off - minimum 10L (depends on size of solar panel), Specifically XXX, and any solar panel (minimum 90 watt).


### Mous Pro Tip - Overkill is best. More power. Bigger batteries, bigger batteries, more protection.


### Solar Power


#### Type

	Just like batteries, choosing the right solar panel for your setup can be a daunting task considering the number and types of panels available, but usually your local wholesale retailer of solar panels can help you with picking one out. There are a few different types of solar panels, but the two main ones we deal with are **monocrystalline **and **polycrystalline**. The main difference between the two is that monocrystalline cells are on average more expensive, but provide more efficiency and have greater heat tolerance; however, performance appears to vary considerably by manufacturer. Panel efficiency is not necessarily important considering the relatively small panels that we use to begin with. Heat tolerance may be an important consideration in more southern latitudes; we recommend speaking to local suppliers for their recommendation. We generally recommend polycrystalline solar panels to save on costs.


#### Wattage

The amount of power your panel needs to produce depends on the amount of sun exposure you expect on the shortest day of the year. In Canada, 80 Watt panels have been effective for ¾ of the year, but do not produce enough for continuous operation in the winter. For continuous winter operation, we have been recommending at leasted approximately 150 Watts by industry experts. In the summer, 50 Watt panels have been sufficient.


#### Charge Controller

All solar panel setups require a charge controller. This is the device that mediates the power flow between the solar panel and the battery, keeping the panel from overcharging the battery, and ensuring electricity doesn’t flow into the panel at night when the panel voltage drops. We recommend getting a charge controller that also includes undervoltage protection, or ‘low-voltage cutoff’, to further protect the battery from getting overly drained by the receiver, or ‘load’. If your charge controller does not have undervoltage protection, a separate device should be used between the battery and load. See

<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "undervoltage protection"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[undervoltage protection](#heading=h.wkgzusibnpq8) for more details.

The charge controller most often used by Birds Canada staff is the [MorningStar SunSaver SS-10L-12V](https://www.morningstarcorp.com/products/sunsaver/). This can charge a 12-volt battery with up to 10 Amps of current and includes a low-voltage cutoff. These have proven robust and longer-lasting than cheaper models, but they can still fail so it’s always important to have spares around.




# Station Installation


## Motus Pro Tip - Do not take short-cuts. Any short-cuts or sloppy workmanship drastically increases the chance that some kind of problem will occur and the station won’t be operating when you need it to.


## Antenna and Coax Assembly

Several varieties of antennas exist of which only a few will be covered here. All antennas should come with their own assembly instructions which are more or less easy to follow so we will not go into great detail here. Please see

<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "antenna anatomy"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[antenna anatomy](#heading=h.qvkiycpcynyy) for more details on parts.

_Note: The driven element and the attached connector are the most sensitive parts of a Yagi antenna; pay special attention to prevent damage to these parts and any connections. Damage to the driven element may cause the antenna to no longer be tuned to the desired frequency resulting in an ineffective antenna._


### Recommended accessories



*   **Coax seal. **This is a type of soft rubber or silicone which is used to seal antenna connections. This is typically purchased separately from the antenna. Marine Goop (with UV protectant (link), and electrician, or plumbers puddy (with link).
*   **Coloured electrical tape or markers. **It can be difficult to keep track of which antenna corresponds with which cable once a station has been set up. Bring a few colours of electrical tape so you can colour code the antennas and coaxial cables.
*   **Zip ties, cable ties, zap straps. **These are indispensable for coaxial cable organisation. Used to support the coax cable along the antenna boom and mast.
*   **Hex nuts and bolts. **We use ¼” x 2” bolts for tripod assembly and ¼” x 1” bolts for affixing solar panels to the tripod**. **Use zinc-plates steel unless the station is deployed in a marine area where stainless steel should be used.


### Antenna mount

Antennas are usually attached to a metal pipe or mast using a type of mounting bracket. Small antennas, like 434 MHz Yagis, all omni antennas, and 3- to 5- element Yagis for the 150-166 MHz band can be butt-mounted using a bracket which fits onto one end of the boom. Large antennas, like 6- to 9- element Yagis for the 150-166 MHz band need to be mounted along their mid-point to even out the lateral force on the mast. Larger antenna can be butt-mounted, but usually require support wires attached to the mid or end point of the antenna.

Nearly all antenna mounts use a metal plate with 4 u-bolts; 2 for the antenna boom and 2 for the mast. For most antennas, the boom is mounted perpendicular to the mast, but omni antennas will often be mounted pointing straight up, meaning both the antenna and mast will be in the same orientation.


### Coax connector

Most antennas will have a connector on the driven element for the coax cable to be connected. The driven element and this connector are the most sensitive parts of a Yagi antenna; pay special attention to these parts so they are not impacted by anything. Damage to the driven element may cause the antenna to no longer be tuned to the desired frequency.

Connecting


## Storage Container Assembly

What’s the purpose of the storage container - primarily to store and protect battery and charge controller.


## Include recommendations to mount receivers on the mast or outside of a box on the ground where possible, or if there is any remote risk of flooding. It will also reduce potential damage from rodents and insects.


### Heavy-duty Container


#### Motus Pro Tip - DO NOT USE cheap plastic rubbermaid, or other plastic storage boxes that are not meant to be kept outside for extended periods of time.


#### Supplies



*   90L Rubbermaid Action Packer or equivalent heavy-duty, waterproof container.
    *   If using an alternative, ensure the container is actually waterproof and the lid is not concave such that water pools on top. Handles will need to be closed securely either with zip ties or a lock.
*   To prevent water ingress:
    *   2-inch pipe elbow (90 degrees) similar to: [NIBCO 2 in. ABS DWV 90-Degree H x H Vent Elbow-C5807VHD2](https://www.homedepot.com/p/NIBCO-2-in-ABS-DWV-90-Degree-H-x-H-Vent-Elbow-C5807VHD2/100344401)
    *   2-inch pipe bushing, similar to: [2 in. x 1-1/2 in. ABS DWV Spig. x Hub Flush Bushing-C58012FHD2112](https://www.homedepot.com/p/2-in-x-1-1-2-in-ABS-DWV-Spig-x-Hub-Flush-Bushing-C58012FHD2112/100342353)
    *   Electrical tape or ABS cement
*   Zip ties
*   Wooden blocks or table for container to sit on (e.g.: 2-foot blocks cut from a 2x4).
*   Wood screws.
*   [Optional] To prevent insects and rodent ingress
    *   Plastic bags and/or steel wool.
    *   Aluminum window screening.
    *   JB Weld epoxy or equivalent.
    *   Container and stir stick for epoxy.
    *   Tool to cut into underside of container (e.g.: exacto knife).


#### Tools



*   Drill
*   [2” hole saw ](https://www.homedepot.com/p/Milwaukee-2-in-Hole-Dozer-Bi-Metal-Hole-Saw-with-3-8-in-Arbor-Pilot-Bit-49-56-9667/202327737)
*   Drill bits for screws


#### Instructions



1. Drill 2” hole on one end of the Action Packer
2. To prevent water ingress:
    1. Place the 2-inch pipe bushing through the hole from the inside of the bin.
    2. Apply a single layer of electrical tape or ABS cement to the exposed end of the bushing on the outside of the bin.
    3. Attach the 2-inch pipe elbow to the bushing and force into place with the open end of the elbow pointing down.
3. To prevent insect and rodent ingress
    4. Cut a hole in the bottom of the container to allow water to drain.
    5. Cut a piece of aluminum window screen about 1 inch (2.5 cm) larger than the hole.
    6. Prepare the epoxy
    7. Place the piece of aluminum window screen over the hole and apply a generous amount of the mixed epoxy around the entire edge, ensuring no gaps remain.
    8. Once you have inserted all necessary cables into the bin, including your GPS and SensorGnome, you will need to pack the remaining space in the elbow with plastic bags (insects) and/or steel wool (rodents).
    9.
4. Insert cable into the case
5. To prevent insect and rodent ingress through the elbow, you will need to pack the remaining space in the elbow with plastic bags (insects) and/or steel wool (rodents).


## Power Assembly


### Solar Power


#### Supplies



*

<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Solar Panel"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Solar Panel](#heading=h.191fxb7jhtpm)
*

<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Battery"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Battery](#heading=h.pie9durjuicv)
*

<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Charge Controller"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Charge Controller](#heading=h.6chq1w9ghov0)
*   [14 AWG Spade connectors ](https://www.homedepot.com/p/Gardner-Bender-16-14-AWG-4-6-Stud-Spade-Terminal-Vinyl-Blue-10-Pack-15-113/205846650)and [stripper/crimping tool](https://www.homedepot.com/p/Klein-Tools-Klein-Kurve-Multi-Tool-Wire-Stripper-Crimper-1019SEN/305303655)
*   [https://www.kleintools.com/catalog/combination-cutting-tools/katapult-wire-stripper-and-cutter-solid-and-stranded-wire](https://www.homedepot.com/p/Klein-Tools-Klein-Kurve-Multi-Tool-Wire-Stripper-Crimper-1019SEN/305303655)


#### Tools



*   Phillips screwdriver
*   Small flathead screwdriver


#### Instructions



1.


## Pop-Tower Assembly

A pop-tower is a type of standalone station that uses a tripod + telescopic mast assembly to mount the antennas. The tripod can be used to mount a solar panel if necessary.


### Prerequisites


#### Location



*   Must be flat and void of obstructions so antennas have a clear line of site.
*   Cannot be near any elevated power or telephone lines for safety reasons.
*   Tripod feet will sink into soft ground - use gravel or choose a hard/dry location to install. Also affix pieces of wood to each trippod foot to support the weight and movement and to provent sunking (‘snow-shoe).
*   Ground must be soft enough to insert anchors (1 m/3 ft. or more, depending on hardness).
*   Choose a well-elevated site to avoid any risk of flooding during heavy rains or tidal surges.
*   Footprint of a pop-tower with guy wires has a radius equal to 70% of the tower’s final height.


#### Hardware



*   Pop tower
    *   Tripod
    *   Wooden blocks (optional)
    *   Mast
        *   Height will depend on location, desired detections.
    *   Foot for mast (optional)
    *   Guy wires
    *   Quick links and/or carabiners (max 3/16”)
    *   [Optional] Turnbuckles and stainless steel wire (snare wire)
    *   In-line wire tensioners.
    *   Anchors
        *   Can use #6 rebar in 5-foot sections or [ground anchors](https://www.homedepot.com/p/6-Piece-Ground-Anchor-Kit-IS-50016/202197240).
*

<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Antennas"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Antennas](#heading=h.8iwn8py4mxon)
*

<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Coaxial Cable"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Coaxial Cable](#heading=h.jxz2pcnpgjrl)
*

<p id="gdcalert21" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "Automated Receiver"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert22">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[Automated Receiver](#heading=h.por17mfiq8m0)


#### Tools



*   Impact driver and/or ratchet
    *   7/16” socket
    *   ½” socket
*   Ratchet with ½” drive
*   Drill
    *   Metal bits
    *   Phillips/Robinson’s for screws


### Instructions


#### Tripod + Mast Assembly



1. Assemble the tripod according to instructions provided by the manufacturer.
    *   It is easiest to install the TRM-10L with it lying on its side.
2. Insert mast into the center of the tripod. Bolts on the tripod may need to be loosened to allow space for the mast to slide through.
3. Attach foot to base of mast.
4. Attach lower guy wires to the lower guy ring using quick links or carabiners.
5. Place tripod + mast assembly upright.
6. Position the assembly so the mast stands level and the tripod legs are on stable ground.
7. Screw on wooden blocks to the tripod legs to prevent them from sinking into the ground. This is suggested for most installations as the ground will soften in the spring and fall.
    *   Alternatively, you can bury cement blocks filled with sand for each foot to stand on.
8. If you are mounting a solar panel, rotate the tripod so that the ‘ladder’ side with four crossbars is facing south.
9. Place three anchors 7 feet (2 m) from the base of the mast such that once the guy wires are attached they are between the tripod legs.
    *   If using angle iron
10. Attach the loose end of the lower guy wires to each anchor.
11. Tighten the guy wires with:
    *   In-line wire tensioner:
        1. Remove tensioner lock.
        2. Place guy wire in the slot of tensioner.
        3. Insert ½” drive ratchet into square slot of tensioner.
        4. Use the ratchet to tightly spool guy wire until taught, but not too taught.
            *   Tripod legs will lift off the ground if too tight, or the mast will bend.
        5. Insert tensioner lock in opposing holes to keep guy wire in place.
        6. Multiple tensioners may be necessary if there is too much excess guy wire.
    *   Turnbuckle: [https://www.youtube.com/watch?v=zz_nS79_JDg&t=386s](https://www.youtube.com/watch?v=zz_nS79_JDg&t=386s)
        7. Before all guy wires are taught, loosen the turnbuckle until only 2 full turns remain.
        8. Tighten guy wires, either with in-line wire tensioners or another method.
        9. Use turnbuckles to finely adjust wire tension until all sides have equal tension.
        10. Use stainless steel wire to immobilize the turnbuckle using the [double-wrap method.](https://www.youtube.com/watch?v=zz_nS79_JDg&t=385s)
12. Confirm tower is being held securely in place by guy wires.


#### Mounting Antennas



1. With antennas assembled w
*




# Testing Receiver Antenna Ranges Using a Tag

_Please send any comments or additions to [motus@birdscanada.org](mailto:motus@birdscanada.org)_

Estimated antenna detection ranges (“[radiation patterns](https://en.wikipedia.org/wiki/Radiation_pattern)”) are purely theoretical and based on ideal conditions so they do not actually reflect the true ranges or shapes of any real antenna (Taylor et al 2017; Crewe et al. 2019). The actual range of an antenna is not easy to calculate because it depends on several factors such as: transmitted signal (by a tag), antenna type and orientation, length and type of coaxial cable, receiver type, and environmental conditions. Best estimates of mean or max antenna ranges are based primarily on biological data when simultaneous detections are recorded by antennas from different stations.

Test tags have been used to try and get estimates of antenna ranges in specific situations (Crewe et al. 2019) and in drone tests (Tremblay et al. 2017; Desrochers et al. 2018; Moore 2020).

Test tag trials can take a lot of time and are not always necessary beyond simply confirming the station is working and an antenna capable of detecting tags nearby. The amount of information you require about antenna range will differ depending on the purpose of your station and the information found in trials may not be representative of actual antenna performance. It is also important to understand the physical limitations of antennas if they are surrounded by trees, or if there is a building or hill in the line of sight that may not always be apparent. Free tools such as [Google Earth](https://support.google.com/earth/answer/3064261?hl=en) and [HeyWhat’sThat](https://www.heywhatsthat.com/) can be used to find the ‘viewshed’, or line-of-site, of any given point and altitude.

Before you get started you should know that it is extremely difficult to emulate the performance of tags as they exist on living animals, the heights and flight directions of potential animals, and antennas, stations detecting living animals.

The following are suggested methods should you like to try and test the local range of a station and antennas.


## Tag Test Methods


### Supplies needed



*   Lotek or CTT tag (activated)
*   GPS with tracking on (a phone can work). Make sure units are set to LAT/LNG (WGS84)
*   A stick or other non-conductive rod
*   Dummy body: A small fruit (grape or clementine), tubed meat (sausage, hot dog), or frozen dead animal. _Differences between these objects are not well tested - take your pick._
*   Water bottle
*   Optional: helium balloon and lots of string
*   Optional: a drone


### Making a dummy



*   Take your activated tag and affix it to the dummy body using tape or string.
    *   The purpose is to simulate the water content (i.e., capacitance) of an animal that is roosting such that the tag transmits a signal that resembles one coming from an actual bird. Keep in mind this is purely based on theory and is not an actual substitute for a real animal.
*   Make sure the antenna hangs off the dummy in a similar orientation you’d expect it to be on your study species.
*   This is required to stimulate tag performance for Lotek tags. Performance of CTT tags is not dependent on being affixed to an animal.


#### Ground simulation

To simulate an animal on or close to the ground, affix the dummy animal to a stick.


#### Flight Simulation

To simulate an animal in the air, affix the dummy animal to a helium balloon._ Note: balloons made from metalized mylar might influence signal transmission. _


### Conducting the test



*   With the tracking on, ensure your GPS has your location so that you can later download your track and correlate it with your tag detections. You may want to download a track ahead of time to make sure you know it works.
*   While holding either the stick or the balloon, walk in concentric circles around the station of growing radius while trying to keep the tag at the same vertical position the whole time.
*   Optionally, you can do this with a drone but don’t ask us how to fly it!
*   It is also extremely difficult to know the position of the dummy within the [radiation pattern](https://en.wikipedia.org/wiki/Radiation_pattern) of the antenna in order to judge peak performance. [See description of different antenna types and radiation patterns here.](https://motus.org/antennas/#antennas)



<p id="gdcalert22" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert23">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")



### Analyzing your results



*   Download your GPS track and extract the timestamp and latitude/longitude for the entire test.
*   Download your receiver data through R following instructions found in the [Motus R Book: Chapter 3](https://motus.org/MotusRBook/accessingData.html).
    *   When using the ‘tagme’ function, make sure you enter the serial number of the receiver you’re testing as the ‘projRecv’ argument, like so:

    _tagme(projRecv = “SG-####RPI3####”, new = TRUE)_

*   You can now correlate your tag’s position with when detections occurred.


### Notes

You may be able to test two tags at different vertical positions simultaneously, but if they have the same burst interval there’s a good chance you’ll run into issues with aliased tags. I won’t go into too many details about them here, but essentially aliased tags are false detections that occur when two real tag detections overlap. To avoid this, just make sure you offset each tag activation such that there are at least 0.3 seconds between bursts.


## References

[Taylor, Philip, et al. "The Motus Wildlife Tracking System: a collaborative research network to enhance the understanding of wildlife movement." Avian Conservation and Ecology 12.1 (2017).](https://www.researchgate.net/publication/315716947_The_Motus_Wildlife_Tracking_System_a_collaborative_research_network_to_enhance_the_understanding_of_wildlife_movement)

[Crewe, Tara L., et al. "Detection range of songbirds using a stopover site by automated radio‐telemetry." Journal of Field Ornithology 90.2 (2019): 176-189.](https://onlinelibrary.wiley.com/doi/abs/10.1111/jofo.12291)

[Desrochers, André, et al. "Estimating wildlife tag location errors from a vhf receiver mounted on a drone." Drones 2.4 (2018): 44.](https://www.mdpi.com/2504-446X/2/4/44/pdf)

[Tremblay, Junior A., et al. "A low-cost technique for radio-tracking wildlife using a small standard unmanned aerial vehicle." Journal of Unmanned Vehicle Systems 5.3 (2017): 102-108.](https://www.nrcresearchpress.com/doi/pdf/10.1139/juvs-2016-0021)

[Moore, Jesse. "TRACKING MIGRATORY BIRDS: APPLYING A PASSIVE TRACKING TECHNIQUE USING DIRECTION OF ARRIVAL FROM VHF RADIO TAGS." (2020).](https://digitalcommons.uri.edu/cgi/viewcontent.cgi?article=2837&context=theses)


# General tips



** **


### Minimum bend radius of cables

Bending any kind of electrical cable, including coax, can cause internal breakage of the individual conductive strands that make up each wire (see attached diagram). A single strand breaking doesn’t necessarily stop the cable from functioning, but it does impact its ability to pass current by increasing the electrical resistance of the cable. Over time and with repeated bending, more and more strands will break until the current is too restricted to transmit power or data effectively. You may have encountered this issue with a personal USB cable for charging your phone, for instance. Think of it as bending a copper pipe back and forth until it breaks apart; at first, it may impede, but still allow the flow of water, but eventually the pipe breaks enough – or entirely – such that water can no longer flow freely through the whole length of the pipe.

For USB cables, which have multiple conductors, the minimum bend radius is 7 times the cable radius which is about 2.5 mm for most that we use. That said, you don’t need to measure every bend in all your cables, that would be a huge waste of time. Just be aware of this issue and try to keep them from kinking/don’t  zip or twist tie them tightly.

SensorGnomes with the BBBK computer were built using the shortest possible cable (18 cm) to save on space and to keep cables tidy, but the size forces them to be bent beyond their recommended turn radius (see image attached). That means they are already under stress to start with and repeated use just exacerbates this problem. Using slightly longer cables will help fix this problem, but very long cables run into another problem where it’s easier to have a damaged cable without noticing since a cut or a kink will be harder to see.








# Appendix A: Definitions


<table>
  <tr>
   <td><strong>Collaborators</strong>
   </td>
   <td>Any person who uses Motus for research, education, or otherwise
   </td>
  </tr>
  <tr>
   <td><strong>Receiver</strong>
   </td>
   <td>A computer designed to receive radio signals
   </td>
  </tr>
  <tr>
   <td><strong>Receiver deployment</strong>
   </td>
   <td>Describes a single setup of a receiver station. This includes information such as: number, types, directions, and heights of antennas; location of station, receiver listening frequency, computer serial numbers, type of antenna mounting structure. Deployments are registered on Motus.org.
   </td>
  </tr>
  <tr>
   <td><strong>Coax</strong>
   </td>
   <td>Coaxial cable, typically used to connect antennas to receivers.
   </td>
  </tr>
  <tr>
   <td><strong>CTT<sup>TM</sup></strong>
   </td>
   <td>Cellular Tracking Technologies<sup>TM</sup>
   </td>
  </tr>
  <tr>
   <td><strong>Antenna mount</strong>
   </td>
   <td>The part which connects the antenna to the mounting structure. Typically a metal plate with U-bolts.
   </td>
  </tr>
  <tr>
   <td><strong>Antenna mounting structure</strong>
   </td>
   <td>Usually a mast, but can be anything imaginable, such as a guard rail, a tree, or a wall.
   </td>
  </tr>
  <tr>
   <td><strong>Mast</strong>
   </td>
   <td>A structure used to mount antennas. Typically a metal pipe and often telescopic (pop-up), such as the <a href="http://wadeantenna.com/wp-content/uploads/2019/07/SPEC0047_C01_POP-UP-MAST_MCN0115.pdf">20A and 50A</a> masts.
   </td>
  </tr>
  <tr>
   <td><strong>Tripod</strong>
   </td>
   <td>A three-legged structure used to support a mast. Usually 10-feet (3 m) tall (TRM-10L).
   </td>
  </tr>
  <tr>
   <td><strong>Angle iron</strong>
   </td>
   <td>Can be steel or aluminum. Angled piece of metal typically used to affix solar panels to tripods.
   </td>
  </tr>
  <tr>
   <td><strong>Mast collar</strong>
   </td>
   <td>A ring around the mast typically used to affix guy lines.
   </td>
  </tr>
  <tr>
   <td><strong>DMX</strong>
   </td>
   <td>A triangular tower structure used for more permanent installations. Usually requires a concrete footing or a building for support.
   </td>
  </tr>
  <tr>
   <td><strong>Non-penetrating Roof Mount</strong>
   </td>
   <td>A type of mast mount which does not require anchoring. Typically used on flat roofs. See non-penetrating roof mounts.
   </td>
  </tr>
  <tr>
   <td><strong>SensorGnome</strong>
   </td>
   <td>Open source receiver developed at the Phil Taylor Lab, Acadia University.
   </td>
  </tr>
  <tr>
   <td><strong>CTT SensorStation<sup>TM</sup></strong>
   </td>
   <td>Receiver made by Cellular Tracking Technologies
   </td>
  </tr>
  <tr>
   <td><strong>Lotek SRX</strong>
   </td>
   <td>SRX-series receiver made by Lotek Wireless Ltd.
   </td>
  </tr>
  <tr>
   <td><strong>Tag</strong>
   </td>
   <td>A radio transmitter made by Lotek or Cellular Tracking Technologies<sup>TM</sup>.
   </td>
  </tr>
  <tr>
   <td><strong>Motus Network</strong>
   </td>
   <td>A collaborative network of receivers, transmitters, partners, and researchers which use radio telemetry to study animal movement.
   </td>
  </tr>
</table>



#


# Appendix B: Receiver power consumption table


<table>
  <tr>
   <td><strong>Setup</strong>
   </td>
   <td><strong>Amps</strong>
   </td>
   <td><strong>Volts</strong>
   </td>
   <td><strong>Watts</strong>
   </td>
   <td><strong>Daily Amp-hours @ 24 hr/d</strong>
   </td>
   <td><strong>Daily Watt-hours @ 24 hr/d</strong>
   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v)
   </td>
   <td><p style="text-align: right">
0.01</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
0.125</p>

   </td>
   <td><p style="text-align: right">
0.24</p>

   </td>
   <td><p style="text-align: right">
3</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T )
   </td>
   <td><p style="text-align: right">
0.03</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
0.375</p>

   </td>
   <td><p style="text-align: right">
0.72</p>

   </td>
   <td><p style="text-align: right">
9</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) - NO GPS
   </td>
   <td><p style="text-align: right">
0.135</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
1.6875</p>

   </td>
   <td><p style="text-align: right">
3.24</p>

   </td>
   <td><p style="text-align: right">
40.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + USB Hub
   </td>
   <td><p style="text-align: right">
0.11</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
1.375</p>

   </td>
   <td><p style="text-align: right">
2.64</p>

   </td>
   <td><p style="text-align: right">
33</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) - NO GPS + USB Hub
   </td>
   <td><p style="text-align: right">
0.225</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
2.8125</p>

   </td>
   <td><p style="text-align: right">
5.4</p>

   </td>
   <td><p style="text-align: right">
67.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) - NO GPS + USB Hub + FCD ProPlus (x1)
   </td>
   <td><p style="text-align: right">
0.305</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
3.8125</p>

   </td>
   <td><p style="text-align: right">
7.32</p>

   </td>
   <td><p style="text-align: right">
91.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) - NO GPS + USB Hub + FCD ProPlus (x2)
   </td>
   <td><p style="text-align: right">
0.405</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
5.0625</p>

   </td>
   <td><p style="text-align: right">
9.72</p>

   </td>
   <td><p style="text-align: right">
121.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) - NO GPS + USB Hub + FCD ProPlus (x3)
   </td>
   <td><p style="text-align: right">
0.49</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
6.125</p>

   </td>
   <td><p style="text-align: right">
11.76</p>

   </td>
   <td><p style="text-align: right">
147</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) - NO GPS + USB Hub + FCD ProPlus (x4)
   </td>
   <td><p style="text-align: right">
0.59</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
7.375</p>

   </td>
   <td><p style="text-align: right">
14.16</p>

   </td>
   <td><p style="text-align: right">
177</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) + PPS-GPS
   </td>
   <td><p style="text-align: right">
0.145</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
1.8125</p>

   </td>
   <td><p style="text-align: right">
3.48</p>

   </td>
   <td><p style="text-align: right">
43.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) + PPS-GPS + USB Hub
   </td>
   <td><p style="text-align: right">
0.24</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
3</p>

   </td>
   <td><p style="text-align: right">
5.76</p>

   </td>
   <td><p style="text-align: right">
72</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) + PPS-GPS + USB Hub + FCD ProPlus (x1)
   </td>
   <td><p style="text-align: right">
0.325</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
4.0625</p>

   </td>
   <td><p style="text-align: right">
7.8</p>

   </td>
   <td><p style="text-align: right">
97.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) + PPS-GPS + USB Hub + FCD ProPlus (x2)
   </td>
   <td><p style="text-align: right">
0.415</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
5.1875</p>

   </td>
   <td><p style="text-align: right">
9.96</p>

   </td>
   <td><p style="text-align: right">
124.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) + PPS-GPS + USB Hub + FCD ProPlus (x3)
   </td>
   <td><p style="text-align: right">
0.505</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
6.3125</p>

   </td>
   <td><p style="text-align: right">
12.12</p>

   </td>
   <td><p style="text-align: right">
151.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) + PPS-GPS + USB Hub + FCD ProPlus (x4)
   </td>
   <td><p style="text-align: right">
0.595</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
7.4375</p>

   </td>
   <td><p style="text-align: right">
14.28</p>

   </td>
   <td><p style="text-align: right">
178.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) + PPS-GPS + USB Hub + RTL-SDR (x1)
   </td>
   <td><p style="text-align: right">
0.295</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
3.6875</p>

   </td>
   <td><p style="text-align: right">
7.08</p>

   </td>
   <td><p style="text-align: right">
88.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + BeagleBoneBlack(May-2017) + PPS-GPS + USB Hub + FCD ProPlus (x1) + RTL-SDR (x1)
   </td>
   <td><p style="text-align: right">
0.395</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
4.9375</p>

   </td>
   <td><p style="text-align: right">
9.48</p>

   </td>
   <td><p style="text-align: right">
118.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT - Wi-Fi OFF
   </td>
   <td><p style="text-align: right">
0.15</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
1.875</p>

   </td>
   <td><p style="text-align: right">
3.6</p>

   </td>
   <td><p style="text-align: right">
45</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi ON
   </td>
   <td><p style="text-align: right">
0.165</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
2.0625</p>

   </td>
   <td><p style="text-align: right">
3.96</p>

   </td>
   <td><p style="text-align: right">
49.5</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi ON + FCD ProPlus (x1)
   </td>
   <td><p style="text-align: right">
0.25</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
3.125</p>

   </td>
   <td><p style="text-align: right">
6</p>

   </td>
   <td><p style="text-align: right">
75</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi ON + FCD ProPlus (x2)
   </td>
   <td><p style="text-align: right">
0.34</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
4.25</p>

   </td>
   <td><p style="text-align: right">
8.16</p>

   </td>
   <td><p style="text-align: right">
102</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi ON + FCD ProPlus (x3)
   </td>
   <td><p style="text-align: right">
0.43</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
5.375</p>

   </td>
   <td><p style="text-align: right">
10.32</p>

   </td>
   <td><p style="text-align: right">
129</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi ON + FCD ProPlus (x4)
   </td>
   <td><p style="text-align: right">
0.52</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
6.5</p>

   </td>
   <td><p style="text-align: right">
12.48</p>

   </td>
   <td><p style="text-align: right">
156</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi OFF + FCD ProPlus (x1)
   </td>
   <td><p style="text-align: right">
0.24</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
3</p>

   </td>
   <td><p style="text-align: right">
5.76</p>

   </td>
   <td><p style="text-align: right">
72</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi OFF + FCD ProPlus (x2)
   </td>
   <td><p style="text-align: right">
0.32</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
4</p>

   </td>
   <td><p style="text-align: right">
7.68</p>

   </td>
   <td><p style="text-align: right">
96</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi OFF + FCD ProPlus (x3)
   </td>
   <td><p style="text-align: right">
0.41</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
5.125</p>

   </td>
   <td><p style="text-align: right">
9.84</p>

   </td>
   <td><p style="text-align: right">
123</p>

   </td>
  </tr>
  <tr>
   <td>Charge Controller(SS-10L-12v) + DC Buck converter(PYB10-Q24-S5-T ) + RaspberryPi3Bv1.2(Oct-2018) + GPS-HAT + Wi-Fi OFF + FCD ProPlus (x4)
   </td>
   <td><p style="text-align: right">
0.5025</p>

   </td>
   <td><p style="text-align: right">
12.5</p>

   </td>
   <td><p style="text-align: right">
6.28125</p>

   </td>
   <td><p style="text-align: right">
12.06</p>

   </td>
   <td><p style="text-align: right">
150.75</p>

   </td>
  </tr>
</table>



#


# Appendix C: Parts list


## Antenna mounting structure


<table>
  <tr>
   <td>Category
   </td>
   <td>Part
   </td>
   <td>Model number
   </td>
   <td>Link
   </td>
  </tr>
  <tr>
   <td>Pop-tower
   </td>
   <td>Tripod
   </td>
   <td>TRM-10L
   </td>
   <td><a href="http://wadeantenna.com/product/10-foot-tripod/">Wade Antenna</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Spare ¼” bolts
   </td>
   <td>¼” x 2” hex bolt
   </td>
   <td><a href="https://www.homedepot.com/p/Prime-Line-1-4-in-20-x-2-in-Grade-304-Stainless-Steel-Hex-Bolts-50-Pack-9058462/310465140">Most hardware stores</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Spare ¼” nuts
   </td>
   <td>¼” lock nut
   </td>
   <td><a href="https://www.homedepot.com/p/Prime-Line-1-4-in-20-Grade-18-8-Stainless-Steel-Nylon-Insert-Lock-Nut-20-Pack-9075237/307410008">Most hardware stores</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Spare 5/16” bolts
   </td>
   <td>5/16” x 1” hex bolt
   </td>
   <td><a href="https://www.homedepot.com/p/Everbilt-5-16-in-18-x-1-in-Zinc-Plated-Hex-Bolt-50-Pack-800710/204281546">Most hardware stores</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Spare 5/16” nuts
   </td>
   <td>5/16” lock nut
   </td>
   <td><a href="https://www.homedepot.com/p/Prime-Line-5-16-in-18-Grade-18-8-Stainless-Steel-Nylon-Insert-Lock-Nuts-50-Pack-9075332/310550302">Most hardware stores</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Spare 5/16” nuts
   </td>
   <td>5/16” hex nut
   </td>
   <td><a href="https://www.homedepot.com/p/Everbilt-5-16-in-18-Zinc-Plated-Hex-Nut-25-Pack-802354/204274092">Most hardware stores</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Mast
   </td>
   <td>Telescoping mast
   </td>
   <td><a href="http://wadeantenna.com/product-category/mounts-masts/">Wade Antenna</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Quick links
   </td>
   <td>⅜” Quick link
   </td>
   <td>Any hardware store
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Mast foot
   </td>
   <td>Swivel base
   </td>
   <td><a href="http://wadeantenna.com/product/40-50-20hd-foot-telescoping-mast-swivel-base/">Wade Antenna</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>-
   </td>
   <td>Base plate
   </td>
   <td><a href="http://wadeantenna.com/product-category/mounts-masts/">Wade Antenna</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Guy wire
   </td>
   <td>3/32” stainless steel wire rope
   </td>
   <td>Some hardware stores
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Wire rope thimble
   </td>
   <td>3/32” Thimble
   </td>
   <td><a href="https://www.amazon.ca/gp/product/B07WTS6PP4/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1">Amazon</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Crimping sleeve
   </td>
   <td>3/32” crimping sleeve
   </td>
   <td><a href="https://www.amazon.ca/gp/product/B0038YY2HM/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1">Amazon</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Turnbuckle
   </td>
   <td>5M or ¼” eye to eye turnbuckle
   </td>
   <td><a href="https://www.amazon.ca/gp/product/B0774S5JJQ/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1">Amazon</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Stainless steel wire
   </td>
   <td>20-gauge Snare wire
   </td>
   <td><a href="https://www.homehardware.ca/en/165-20-gauge-stainless-steel-snare-wire/p/7685837">Most hardware stores</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>In-line wire tensioner
   </td>
   <td>In-line wire tensioner
   </td>
   <td><a href="https://www.gallagherfence.net/products/permanent-wire-tightener">Gallagher</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Ratchet
   </td>
   <td>Wire tensioner tool
   </td>
   <td><a href="https://www.gallagherfence.net/products/ratchet-wire-tightening-tool?_pos=1&_sid=52a363e77&_ss=r">Gallagher</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>-
   </td>
   <td>Regular ratchet with ½” drive
   </td>
   <td>Any hardware store
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Carabiner
   </td>
   <td>6M carabiner
   </td>
   <td><a href="https://www.amazon.ca/gp/product/B06XG4QZ5F/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1">Amazon</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Anchor
   </td>
   <td>#6 rebar (5-feet)
   </td>
   <td><a href="https://www.homedepot.com/p/3-4-in-x-20-ft-6-Rebar-PAR402006/205370251">Most hardware stores</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>-
   </td>
   <td>Ground anchor
   </td>
   <td><a href="https://www.homedepot.com/p/6-Piece-Ground-Anchor-Kit-IS-50016/202197240">Home depot</a>
   </td>
  </tr>
  <tr>
   <td>Non-penetrating roof mount
   </td>
   <td>Non-penetrating roof mount
   </td>
   <td>NPRM-series (light- to heavy-duty)
   </td>
   <td><a href="http://wadeantenna.com/product/heavy-duty-non-penetrating-roof-mount/">Wade Antenna</a>
   </td>
  </tr>
  <tr>
   <td>-
   </td>
   <td>Mast
   </td>
   <td>Masting
   </td>
   <td><a href="http://wadeantenna.com/product/masting/">Wade Antenna</a>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>




**Parts description and what to look for (see diagrams on last three pages)**


<table>
  <tr>
   <td><strong>Antennas</strong>

<p id="gdcalert23" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert24">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image9.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description</strong>
<p>
Attached to the top of the <span style="text-decoration:underline;">mast</span>. The <span style="text-decoration:underline;">antenna boom</span> attaches to the <span style="text-decoration:underline;">mast</span> with an <span style="text-decoration:underline;">antenna mounting bracket</span>, and the <span style="text-decoration:underline;">antenna elements</span> attach to the boom. There are usually 9 elements attached to the boom with one <span style="text-decoration:underline;">element</span> that has a <span style="text-decoration:underline;">coaxial cable</span> coming out of it.
<p>
<strong>What to look for: </strong>
<ul>

<li><span style="text-decoration:underline;">Bent elements</span> will affect the signal reception, but usually not that badly unless severely bent (~30 degrees). The most important element is the one that has the coaxial cable. Just take photos of anything bent.

<li><span style="text-decoration:underline;">Loose elements</span>. If they are not all horizontally aligned, they might be loose. Try tightening to bolts.

<li>If the <span style="text-decoration:underline;">antenna directions</span> are wrong, the boom might not be attached to the mast tight enough. Try rotating the antenna by hand and if it’s easy, tighten the u-bolts on the antenna mounting bracket. Add bicycle inner tubes if necessary.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Tripod</strong>
<p>


<p id="gdcalert24" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert25">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image10.jpg" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description: </strong>
<p>
The three-legged support that the <span style="text-decoration:underline;">mast</span> slides into – about 10 feet tall. <span style="text-decoration:underline;">Solar panels</span> are usually mounted here.
<p>
<strong>What to look for: </strong>
<ul>

<li>Is the <span style="text-decoration:underline;">tripod level</span>?

<li>Is the tripod easy to rock back and forth?

<li>Have any of the legs sunk into the ground?
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Mast</strong>
<p>


<p id="gdcalert25" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert26">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image11.jpg" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description</strong>
<p>
The tall metal pole at the center of the tower where the antennas are mounted. It has 3-4 telescopic sections that can be fixed in place by L-bolts.
<p>
<strong>What to look for</strong>:
<ul>

<li>Is it bent?

<li>Does it rotate freely?

<li>Is it being supported by 3 guy wires for every 10’ of height?
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Guy wires and spools</strong>
<p>


<p id="gdcalert26" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert27">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image12.jpg" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description</strong>
<p>
The metal cables that support the mast at every 10’ section. They are attached to the <span style="text-decoration:underline;">mast collar</span> with <span style="text-decoration:underline;">quick links</span>. They are tightened by <span style="text-decoration:underline;">wire spools.</span>
<p>
<strong>What to look for:</strong>
<ul>

<li>Are there 3 guy wires for every 10’ section of mast height?

<li>Are all guy wires tight?

<li>Are there spools missing from the loose guy wires?
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Coaxial cable</strong>
<p>


<p id="gdcalert27" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.gif). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert28">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image13.gif" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description</strong>
<p>
This is what plugs into the antennas and connects to the computer.
<p>

<p>
<strong>What to look for: </strong>
<ul>

<li>Is it firmly connected on both ends?

<li>Are there any cracks or have animals chewed up the cable? If any of the inner metal wiring is exposed you must replace it.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Mast collar & quick links</strong>
<p>


<p id="gdcalert28" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert29">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image14.jpg" width="" alt="alt_text" title="image_tooltip">


<p id="gdcalert29" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert30">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image15.jpg" width="" alt="alt_text" title="image_tooltip">

<p>
<em>   Mast Collar   Quick Link</em>
   </td>
   <td><strong>Description</strong>
<p>
<span style="text-decoration:underline;">Mast collar </span>is a ring that goes around the mast and has hole which holds the <span style="text-decoration:underline;">quick links</span>. <span style="text-decoration:underline;">Quick links</span> are attached to the guy wires.
<p>
<strong>What to look for: </strong>
<ul>

<li>Are the quick links all closed properly?

<li>Are their guy wires attached to each of them?

<li>Is the guy wire fraying where they are attached?
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Solar panel</strong>
   </td>
   <td><strong>Description </strong>
<p>
Attached to the tripod by <span style="text-decoration:underline;">angle iron</span>. It has wires attached to the back of the panel that lead into the <span style="text-decoration:underline;">action packer</span> and plug into the solar charge controller.
<p>
<strong>What to look for: </strong>
<ul>

<li>Is the panel attached firmly to the tripod?

<li>Are there any cracks or chews in the cables?

<li>What is the voltage of the solar panel (check on <span style="text-decoration:underline;">charge controller</span> terminals)?

<li>Is the panel angled correctly? About 30 degrees.

<li>Is the angle iron scratching into the back of the panel?
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Charge controller</strong>

<p id="gdcalert30" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image16.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert31">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image16.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong> </strong>
<p>
<strong>Description</strong>
<p>
Inside the <span style="text-decoration:underline;">action packer</span>, this is the device that controls the power from the <span style="text-decoration:underline;">solar panel</span> to the<span style="text-decoration:underline;"> battery</span> and from the <span style="text-decoration:underline;">battery</span> to the <span style="text-decoration:underline;">computer</span>. There should be six terminals on here, two for each of the solar panel, battery, and computer (computer terminals are labeled as ‘load’).
<p>
<strong><em>Be very careful not to short circuit any of the two terminals!!</em></strong>
<p>
<strong>What to look for: </strong>
<ul>

<li>What color are the battery status LEDs? There should be red, yellow, or green. If more than one are lit, describe the pattern and replace the charge controller. If the LED is red, your battery might be dead.

<li>What color is the charging status LED?

<li>Are the connections tight?

<li>Is there any sign of corrosion or rust?

<li>Check the polarity of all cables: are the positive ends connected to the positive terminals?
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Battery</strong>
<p>


<p id="gdcalert31" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image17.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert32">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image17.jpg" width="" alt="alt_text" title="image_tooltip">

<p>
<em>Fused battery leads</em>
   </td>
   <td><strong>Description</strong>
<p>
Inside the <span style="text-decoration:underline;">action packer.<strong> </strong></span>Plugs directly into the charge controller. Sometimes there is a fuse attached to the positive cable.
<p>
<strong>What to look for:</strong>
<ul>

<li>What is the battery voltage? Anything below 11 volts or above 15 volts is bad.

<li>Are there any signs of corrosion or rust?

<li>Are the connections tight?

<li>If there is a fuse and battery status light on the <span style="text-decoration:underline;">charge controller</span> is red, is the fuse blown?
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Action packer</strong>
<p>


<p id="gdcalert32" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image18.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert33">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image18.jpg" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description</strong>
<p>
The large plastic case that holds the computer (in pelican case) and battery.
<p>

<p>
<strong>What to look for: </strong>
<ul>

<li>Is the lid on properly? Did the last person to visit close it correctly?

<li>Has water collected in the box?

<li>Is the elbow pipe where the cables go into the box pointing upwards? It should point downwards so water doesn’t get in.

<li>Are there holes in the bottom of the box? There should be small holes to allow moisture to get out.

<li>Is the box raised off the ground? It should be so water can drip out of the holes.

<li>Is the box sitting in a wet, low-lying area? If yes, consider raising it a foot or two.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>Computer</strong>
<p>


<p id="gdcalert33" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image19.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert34">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image19.png" width="" alt="alt_text" title="image_tooltip">

<p>
<em>BeagleBone</em>
<p>


<p id="gdcalert34" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image20.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert35">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image20.png" width="" alt="alt_text" title="image_tooltip">

<p>
<em>Raspberry Pi</em>
   </td>
   <td><strong>Description</strong>
<p>
Inside the pelican case, it is a small metal box that’s about 3”x4”x2” and is usually orange or blue. There is usually a red or blue LED blinking and a serial number written on the top. There are two types: Raspberry Pi and BeagleBone. Raspberry Pi has 4 USB ports on one end. Beagle Bone has just one USB port.
<p>
<strong>What to look for</strong>:
<ul>

<li>What is the serial number? Write it down at the top of the checklist.

<li>Are there LED’s on or blinking? Take a video and/or describe their colour and behaviour.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>DC-DC Voltage Converter</strong>
<p>


<p id="gdcalert35" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image21.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert36">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image21.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description</strong>
<p>
This lowers the battery voltage down to something the computer can handle (5 volts). On one end it has wires that connect directly to the <span style="text-decoration:underline;">charge controller</span> load terminals and the other end has a barrel jack or micro USB cord (depend on computer type) that plugs into the computer.
<p>
<strong>What to look for:</strong>
<ul>

<li><strong>ONLY NEEDED FOR SOLAR + BATTERY INSTALLATIONS</strong>

<li>Is the green LED lit up?

<li>Are the wires securely in place?

<li>If LED is off and wires are secure, check voltage of wires and make sure they are connected to the correct terminals.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>USB Hub</strong>
<p>


<p id="gdcalert36" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image22.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert37">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image22.jpg" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description</strong>
<p>
This is only present in BeagleBone computers (you might not have any). They are black with rounded corners and have a green or blue LED that lights up when powered on. It has 7 USB ports on it and some of them have the coaxial cables plugged into them.
<p>
<strong>What to look for: </strong>
<ul>

<li>ONLY NEEDED FOR BEAGLEBONE COMPUTERS

<li>Is the USB hub powered on?

<li>Are all the connections tight?
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><strong>GPS</strong>
<p>


<p id="gdcalert37" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image23.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert38">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image23.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td><strong>Description</strong>
<p>
This is what plugs into the computer with a small SMA adapter (screws in). It’s a small black square (~1.5”) with a long thin cable attached.
<p>
<strong>What to look for: </strong>
<ul>

<li>Is it plugged in to the computer?

<li>Does it have any cracks or tears in the cable?
</li>
</ul>
   </td>
  </tr>
</table>




<p id="gdcalert38" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image24.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert39">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image24.png "image_tooltip")


**Inside Action Packer**



<p id="gdcalert39" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image25.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert40">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image25.png "image_tooltip")


**Inside Computer Case with Raspberry Pi (No USB Hub needed)**



<p id="gdcalert40" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image26.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert41">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image26.png "image_tooltip")


**Inside Computer Case with BeagleBone (USB Hub Present)**



<p id="gdcalert41" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image27.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert42">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image27.png "image_tooltip")


**USB Port Numbering for Raspberry Pi or BeagleBone computers.**

Note <span style="text-decoration:underline;">BeagleBone computers</span> only has 1 USB port so it must use a USB Hub to expand the number of available ports. Raspberry Pi computers have 4 ports so they _do not_ require a USB hub.


<table>
  <tr>
   <td><strong>Raspberry Pi</strong>
   </td>
   <td><strong>USB Hub (for BeagleBone)</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert42" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image28.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert43">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image28.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>

<p id="gdcalert43" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image29.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert44">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image29.png" width="" alt="alt_text" title="image_tooltip">

   </td>
  </tr>
</table>


**Charge Controller Wiring**



<p id="gdcalert44" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image30.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert45">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image30.jpg "image_tooltip")
