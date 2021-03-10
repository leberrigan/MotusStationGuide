# Antennas, Cables, and Dongles

## How to Select an Antenna

It is very important you select the right antenna for the purpose of the station and the type of tags you intend to detect. Antennas are optimized for reception on a particular radio frequency. Since there are multiple tag frequencies, each tag type requires its own antenna; currnetly an antenna optimized to detect Lotek tags on 166.380 Mhz will not detect CTT tags on 434 Mhz, and vice versa. Wherever possible we recommend installing “dual-mode” stations outfitted with antennas and a receiver that can detect tags tags. A dual-frequency antenna is under development, but for the time being, dual-mode stations \(those that can listen for more than one frequency, must have two different types of antenna in place.

An antenna is a device used to send or receive radio signals, i.e., electromagnetic radiation. This radiation induces a voltage in conductive materials which will vary in magnitude based on the physical dimensions and orientation of the material. The induced voltage oscillates at the same frequency as the electromagnetic radiation and the amount of voltage induced is proportional to the strength of the radiation. Antennas used in this network are built \(“tuned”\) with high precision such that the induced voltage is most intense when exposed to a narrow range of frequencies. Antennas can also be shaped to select for radiation from specific directions and orientations.![](https://github.com/leberrigan/MotusStationGuide/tree/0a99925bc5561e87ef911b34594b1ee427d231dc/media/image5.gif)

Each antenna has a theoretical radiation pattern which represents its range in 3D space. We use the radiation pattern to predict the distance and direction we can receive signals from radio transmitters. Omnidirectional \(‘omni’\) antennas, as the name suggests, have a uniform radiation pattern that is emitted perpendicular to its axis. The thin wire attached to Lotek and CTT tags is a type of omni antenna. When used on a receiver, omni antennas provide presence/absence information, typically within a short range. This makes them ideal for fine scale studies and are indeed used with CTT SensorNodes to create a high-resolution grid.

![](https://github.com/leberrigan/MotusStationGuide/tree/0a99925bc5561e87ef911b34594b1ee427d231dc/media/image6.png)![](https://github.com/leberrigan/MotusStationGuide/tree/0a99925bc5561e87ef911b34594b1ee427d231dc/media/image7.gif)

A torus, representing the radiation pattern of an omnidirectional antenna \(left; [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0), source: [Wikipedia](https://commons.wikimedia.org/wiki/File:Simple_Torus.svg)\). Cross-sectional view of a half-wave omni-directional antenna \(right; public domain, source: Wikipedia\).

Yagi-Uda \(‘Yagi’\) antennas are a type of directional antenna that are the most commonly used antenna in the Motus network. Their radiation pattern is directed into a beam which varies in length and width based on the number of ‘directing elements’ with a greater number of elements resulting in a longer, narrower beam. A 9-element Yagi antenna, for instance, can theoretically provide tag detections from 15 km away at 166.380 MHz, but this will vary widely in reality, based on the landscape and atmospheric conditions. Yagi antennas are favorable for most applications since they can be used to create receiver ‘fences’ or ‘grids’ with fewer stations than an omni antennas could. In addition, multiple Yagi antennas on a single station can be used to infer flight direction based on the timing of detection across each antenna.

A variety of antenna options exist for VHF/UHF telemetry. To date, collaborators have used 3, 5, 6, and 9-element Yagi directional antennas, and omni-directional antennas. Generally the greater the number of elements, the longer the detection range and more narrow the detection beam. The fewer the elements, the shorter the detection range, but the broader the detection beam. Omni-directional antennas are best suited for determining species presence-absence patterns \(e.g. seabirds at a colony\), or for detecting birds in close proximity to stations \(within a few hundred metres\), not suited for providing directional information \(e.g. departure directions of songbirds from a stopover site\).

Large Yagi antennas are useful for making receiver fences and grids since they can be spaced as far as 30 km apart with antennas pointing towards each other to capture animals passing in between. Mid-sized Yagi antennas provide a compromise between distance and “field of view”, or width of the detection beam. Small Yagi antennas are typically used for manual tracking, or for monitoring animals within a small study area. [CTT Nodes](https://celltracktech.com/products/tag-system/ctt-node/) have small omni antennas with a line-of-sight \(LOS\) range of around 1.4 km which if distributed in a grid can provide highly accurate location estimates. See array design above.

## Ordering Antennas

When ordering antennas and cables, it is important to ensure:

1. Connectors between the coaxial cable, antennas, and receiver are compatible.
2. The impedance rating of all cables, connectors, and dongles are the same \(50 Ohms\).
3. Cable type is suitable for the length needed.
4. Get recommended equipment if inexperienced with the technology \(highlighted in green\).

Select an item from the list below to learn more:

* [Antennas](https://motus.org/antennas/#antennas)
* [Coaxial Cables](https://motus.org/antennas/#cables)
* [Radio Dongles](https://motus.org/antennas/#dongles)
* [Connectors](https://motus.org/antennas/#connectors)

## Antenna Anatomy

### Yagi-uda

This antenna, usually referred to as simply “Yagi” or more generally a directional antenna.

## ![](https://github.com/leberrigan/MotusStationGuide/tree/0a99925bc5561e87ef911b34594b1ee427d231dc/media/image8.png)

## Antenna Types

A variety of antenna options exist for VHF telemetry. To date, users have used 3, 5, 6, and 9-element Yagi directional antennas, and single-pole omni-directional antennas. The 9-element Yagis have a long, narrow detection range, whereas 3, 5, or 6-element Yagis have gradually shorter and wider detection ranges. Omni-directional antennas are best suited for determining species presence-absence patterns \(e.g. seabirds at a colony\), or for detecting birds in close proximity to stations \(within a few hundred metres\), but not for providing directional information \(e.g. departure directions of songbirds from a stopover site\).

When ordering antennas, it’s important to know what frequency you need it to be tuned to. For detecting Lotek tags, antennas must be tuned to 150.1 MHz \(Europe\), 151.5 MHz \(Australia\), or 166.380 MHz \(Western Hemisphere\), depending on the region. For detecting CTT tags, antennas must be tuned to 434 MHz.

Antennas can be purchased from the following suppliers:

* [Laird](https://www.arcantenna.com/plc1669-laird-yagi-heavy-duty-9-element-antenna-for-166-174-mhz-with-uhf-female-connector-track-migratory-birds.html) \(through Hutton in Canada Economy 2-way in US\)
* Wade Antenna \[LINK\]
* [Maple Leaf Communications](http://www.mapleleafcom.com/)
* [Digikey](http://www.mapleleafcom.com/)

Use the table below to help select your antenna:

| **Antenna type** | **Typical price \(USD\)** | **Impedence** | **Theoretical range** | **Veiw** |
| :--- | :--- | :--- | :--- | :--- |
| **3-element Yagi** | $$$ | 50 Ohms | ~5 km | Wide directional |
| **5-element Yagi** | $$$ | 50 Ohms | ~8 km | Directional |
| **6-element Yagi** | $$$ | 50 Ohms | ~10 km | Directional |
| **9-element Yagi** | $$$ | 50 Ohms | ~15 km | Narrow directional |
| **Omnidirectional** | $$$ | 50 Ohms | ~1 km | Omnidirectional |
| Items listed in green are recommended. |  |  |  |  |

## Coax Cables

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Cable type</b>
      </th>
      <th style="text-align:left"><b>Typical price (USD)</b>
      </th>
      <th style="text-align:left"><b>Impedance</b>
      </th>
      <th style="text-align:left">
        <p><b>Max attenuation</b>
        </p>
        <p><b>(dB/100 ft)</b>
        </p>
      </th>
      <th style="text-align:left"><b>Suggested length</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><a href="https://www.pasternack.com/flexible-0.195-rg58-50-ohm-coax-cable-pvc-jacket-rg58c-u-p.aspx"><b>RG-58</b></a>
      </td>
      <td style="text-align:left">&lt; 100 ft. @ $0.83/ft.</td>
      <td style="text-align:left">53.5 Ohms</td>
      <td style="text-align:left">
        <p>4.4 @ 100 MHz</p>
        <p>6.0 @ 200 MHz</p>
        <p>8.5 @ 400 MHz</p>
      </td>
      <td style="text-align:left">&lt; 50 ft./15 m</td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="https://www.pasternack.com/flexible-0.405-rg213-50-ohm-coax-cable-pvc-jacket-rg213-u-p.aspx"><b>RG-213</b></a>
      </td>
      <td style="text-align:left">&lt; 100 ft. @ $1.79/ft.</td>
      <td style="text-align:left">50 Ohms</td>
      <td style="text-align:left">
        <p>2.3 @ 100 MHz</p>
        <p>4.8 @ 400 MHz</p>
      </td>
      <td style="text-align:left">&lt; 100 ft./30 m</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>TWS/BMR/</p>
        <p><a href="https://www.pasternack.com/50-ohm-low-loss-flexible-lmr400-pe-jacket-double-shielded-black-lmr-400-P.aspx"><b>LMR-400</b></a>
        </p>
      </td>
      <td style="text-align:left">$1.20/ft.</td>
      <td style="text-align:left">50 Ohm</td>
      <td style="text-align:left">
        <p>1.5 @ 150 MHz</p>
        <p>2.7 @ 450 MHz</p>
      </td>
      <td style="text-align:left">Any length</td>
    </tr>
  </tbody>
</table>

A helpful guide on coaxial cables can be found on the [Wilson Amplifiers website](https://www.wilsonamplifiers.com/blog/understanding-coaxial-cables-the-complete-guide/)

A catalogue of cables and their specifications can be found on [Allied Wire & Cable](https://www.awcwire.com/producttoc.aspx?id=coaxial-cable).

* **RG58** – basic communications cable that typically comes with a BNC connector. Best used for lengths less than 50′. The least expensive option.
* **RG213** – higher grade cable that can be used at length of up to 100′ with low signal loss. Custom cable ends depending on distributor/manufaturer. Moderate price.
* **TWS/LMR-400** – similar to the RG-213, but higher quality \(stronger weather/sun resistance\) coating. Best for longer-term installations and long cable length. Most expensive. Manufacture can suggest which cable is best for your needs – LMR is generally more affordable.
* **BMR-400** - available from Maple Leaf Communications, this cable has slightly less plastic insulation, making it much more flexible and easier to work with than LMR-400, while offering similar attenuation.

{% hint style="info" %}

**Motus Pro Tip** - The heavier guage cables can be buly to work with and awkward to connect inside the receiver. Short jumper cables with smaller guage can be used to help work in tight spaces. Insert picture and example from Maple Leaf. However, this does increase the number of connections which may result in a slight decrease in signal strength \(see connectors below\).

{% hint style="info" %}

## Radio Dongles

Radio dongles, also known as Software Defined Radios \(SDRs\), are used to convert analog signal received by the antennas into a digital signal that can be interpreted by the SensorGnome . Note that Lotek receivers have a built-in converter and do not require these for station operation. Note that SensorStations only need an SDR for antennas tuned for Lotek tags \(anything that isn’t 434 MHz\).

While there are dozens of available SDR’s on the market, only four models are compatible with SensorGnomes and SensorStations. Most commonly used are the **FUNcube Pro Plus** which have the smallest signal-to-noise ratio \(_SNR_\), _noise figure_, and _DC voltage spike_ \(poor reception at nominal frequency\), and power rating. However, FUNcube dongles are the most expensive, costing ~$200 USD, compared to $35 USD for the **RTL-SDR**. Despite the high price, we currently recommend FunCubes as the other SDR’s have not been properly tested or optimized for use. See the table below for more information:

| **Receiver** | **Price \(USD\)** | **Power in use** | **Power while idle** | **Reliability** | **Typical noise figure** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **FUNcube Pro Plus** | $225 | 0.8 W \(48 kHz\) | 0.8 W \(48 kHz\) | Very reliable | 3.5 dB @ 145 MHz |
| **RTL-SDR blog V3** | $22 | 1.5 W | 0.7 W | Unknown | ~5 dB @ 144.3 MHz |
| **NESDR SMArt v4** | $24 | 1.54 W | &lt;0.25 W | Unknown | Unknown |
| **NESDR SMArtee** | $26 | 1.43 W | Unknown | Unknown | Unknown |
| **NESDR Smart XTR** | $38 | 1 W | 0.6 W | Unknown | Unknown |
| **CTT\*** | $100 | &lt;0.25 W | &lt;0.25 W | Unknown | Unknown |

\* CTT dongles listen to 434 MHz and are only used to make Sensorgnomes compatible with CTT tags.

Items listed in green are recommended.

## Connectors

There are several types of connectors that are used with radio antennas and coaxial cables, but not all perform equally. For instance, certain connectors are better at preventing water and dust ingress. For this reason, it’s important to know what kind of connectors your antennas have when being purchased, and which are most suitable for a Motus station. There are four connector types commonly found in Motus station setups: _UHF_ \(_PL-259_\); _N-type_; _BNC_; and _SMA_.

Most 9-element Yagis and omni-directional antennas tend to come with a female UHF \(Laird\) or N-type connector \(Maple Leaf\), but this should be verified prior to purchase. Three and 5-element Yagis usually come with a male BNC connector and so they can be connected to a Lotek SRX receiver directly, or to a FUNcube with female BNC to male SMA adapter.

The following table outlines where we typically see these connectors. Dongles are the analog-to-digital converters that are part of the Sensorgnome \(typically we use FUNcube dongles, or FCD\).

| **Connector** | _Antenna_ | _Cables_ | _Radio Dongles_ | **Water resistance** |
| :--- | :--- | :--- | :--- | :--- |
| **UHF** | Common | Common | Never | Good |
| **N-type** | Common | Common | Never | Best |
| **BNC** | Some Lotek | Common | Never | Poor |
| **SMA** | Never | Some adapter cables GPS cables | Always | Good |

Items listed in green are recommended.

The following are some common uses of these connectors:

1. Coax cable with male BNC connector at one end and male UHF connector at the other end \(for Lotek receivers or Sensorgnomes with female BNC to male SMA adapter\).
2. Coax cable with a male BNC connector at both ends with a BNC female to UHF male adapter \(Lotek receivers or Sensorgnomes with female BNC to male SMA adapter\).
3. Coax cable with custom female UHF connector at the antenna end and a male SMA connector at the FUNcube end. \(Option with fewest adapters and therefore less signal loss, but may be more expensive due to custom ends\). Sensorgnome only.

{% hint style="info" %}

**Motus Pro Tip** - Every connection, every adapter, may result in lowering the sensitivity of station to detect tags. Make every effort to minimize the number of connections/adapters between the antenna and the receiver.

{% hint style="info" %}

