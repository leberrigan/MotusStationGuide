# Power

You can’t have a reliable station without a reliable power source. For this reason, it’s best to ensure more than an ample supply is available.

## Power Sources

Receivers can be powered by either AC or DC. AC power supplied by mains should be used whenever possible as it is generally a more reliable and cheaper power supply than DC. DC supplies usually come in the form of Deep Cycle batteries and require regular charging via solar or another method to maintain power. Also keep in mind that since DC typically requires a solar panel and battery it is a more attractive target for thieves.

### AC Supply

If using mains AC power from a typical wall outlet, ensure you use a good quality power adaptor that is rated for the mains power of that region \(e.g.: North America is 120 Vrms @ 60 Hz; South America is [highly variable](https://www.tripsavvy.com/south-america-outlets-and-adapters-1637155), 115-230 Vrms @ 50 or 60 Hz\). A good quality adaptor can tolerate this variation in mains voltage which makes them more versatile for projects across multiple countries. A poor quality adaptor will produce an unstable voltage which can damage a receiver or not produce enough power to keep it operational. You may also want to connect your station through a proper surge protector.

The type of adaptor required will depend on the type of receiver being used. For CTT SensorStations and Lotek SRX receivers, these power supplies are usually included with the receiver. SensorGnomes will also be shipped with an AC power supply when ordered through Compudata or RFS Scientific.

If you do not have a power adaptor for your SensorGnome receiver, you can use a standard USB power supply for your phone \(“fast charger” or minimum of 2.5 Amps\) with a USB cable. For CTT or Lotek receivers, contact your supplier to purchase an adaptor.

If mains power is unreliable and 24/7 coverage is needed, then you may wish wish to connect your station through a battery powered backup power supply.

### DC Supply

Powering electronics directly from DC is more complicated since there is no single setup for all stations. Instead, the type and amount of power required will depend largely on region and available resources. In order for a station to be compatible with a DC power supply, it must have a method for converting the voltage of a battery - usually 12 volts - to something the receiver can handle, which ranges from 5 to 18 volts, depending on the model.

* CTT SensorStations have built-in voltage converters, allowing them to accept a direct connection to the battery; however, in practice NEVER connect your receiver directly to the battery without a [low-voltage cutoff](power.md#undervoltage-protection) to protect your battery.
* SensorGnomes, require a DC buck converter to lower the voltage down to 5 volts. Buck converters are only provided in SensorGnomes if requested when purchasing from Compudata or RFS Scientific.
* Contact Lotek or see your receivers user manual for more information on SRX series receivers.

### Battery

#### Type

**Lead-acid batteries** are based on very old technology, but still provide the cheapest, non-volatile power storage for electronics. Lithium-based batteries offer the highest energy density of any commercially available battery, yet they are far more expensive relative to the power they store. In addition, Lithium-based batteries are typically far more volatile, risking chemical spills and fire if they are charged/discharged too quickly, if their temperature is too high or if they are punctured. For these reasons we do not recommend Lithium-based batteries unless space and weight is very limited. Since lithium-based batteries are used so rarely in the Motus network, they will not be discussed further here.

Most people refer to 12-volt lead-acid batteries as “car batteries,” but in this instance you might get the wrong type if that’s what you ask for. This is because car batteries are not designed to be discharged over long periods of time and require constant top-ups, such as from a car’s alternator. In a Motus station, batteries must be able to go down to voltages as low as 10-11 volts each night without losing much capacity - this would ruin the typical car battery in no time!

This is why we use **deep-cycle batteries** which allow a deep discharge during each charging cycle. Most deep-cycle batteries that are readily available are marine grade \(a.k.a.: “marine battery”\) which are designed around offering high cranking amps to start up large boat motors, but this is not anything we need in a radio station. Nonetheless, in remote locations with nothing else available, a marine battery will do. While more expensive, specialize solar deep-cycle batteries are also available that are designed provide small amounts of power continuously and varying degress of recharging.

You may also notice there are **flooded** and **sealed lead-acid** \(SLA\) batteries that exist. This refers to whether the internal chemistry can offgas externally. Flooded lead-acid batteries are well known for producing highly flammable hydrogen gas and can be extremely hazardous if not stored in a well-ventilated area. We usually store batteries in a closed tupperware bin which increases the potential of this hazard which is why we recommend **SLA batteries.** Even so, batteries should be handled with care so as to not puncture the battery casing, potentially allowing the slow release of hydrogen gas over time.

We recommend the use of Trojan batteries \(minimum XX amp/hour\), specifically XXX.

#### Capacity

Battery capacity is recorded in Amp-hours \(Ah\) or Watt-hours \(Wh\) which is a measurement of current or wattage consumed multiplied by the amount of time current flows. This is helpful because we can easily calculate the amount of Amp-hours we expect our receiver to consume by reviewing the [_power consumption table_](power.md#appendix-b-receiver-power-consumption-table) or by measuring the current of a connected receiver using a voltmeter. Put simply, a SensorGnome which consumes 0.5 A of power at ~12 volts can theoretically run off a 50 Ah battery for 100 hours \(50 Ah / 0.5 A = 100 h\). Keep in mind that you won’t ever use the full capacity of a battery since it should not be discharged below 10.5 volts \(see [Undervoltage Protection](power.md#undervoltage-protection)\). In addition, the capacity will slowly decrease over time with each discharge of the battery, so ensure you add an extra 10-15% of capacity to account for this drop over time. Batteries vary in performance at different temperatures as well and average a shorter lifespan in warmer climates.

When shopping for batteries, we recommend a 50 Ah battery for day lengths greater than 12 hours and a 75 Ah for day lengths under 12 hours.

#### Undervoltage Protection

When using any type of battery to power a station, it is recommended to _**always**_ use undervoltage protection so you do not ruin your battery. While your station may function without one, it greatly reduces battery life and will eventually result in the battery not holding any charge. If using a solar panel to charge the battery, you will require a [charge controller with low voltage cutoff](power.md#charge-controller). Without a charge controller, you will need to buy a low voltage cutoff, also known as an undervoltage protection module.

We recommend Sunsaver charge controllers with low-voltage cut-off - minimum 10L \(depends on size of solar panel\), Specifically XXX, and any solar panel \(minimum 90 watt\).

{% hint style="info" %}

**Motus Pro Tip** - Overkill is best. More power. Bigger batteries, bigger batteries, more protection.

{% hint style="info" %}

### Solar Power

#### Type

Just like batteries, choosing the right solar panel for your setup can be a daunting task considering the number and types of panels available, but usually your local wholesale retailer of solar panels can help you with picking one out. There are a few different types of solar panels, but the two main ones we deal with are **monocrystalline** and **polycrystalline**. The main difference between the two is that monocrystalline cells are on average more expensive, but provide more efficiency and have greater heat tolerance; however, performance appears to vary considerably by manufacturer. Panel efficiency is not necessarily important considering the relatively small panels that we use to begin with. Heat tolerance may be an important consideration in more southern latitudes; we recommend speaking to local suppliers for their recommendation. We generally recommend polycrystalline solar panels to save on costs.

#### Wattage

The amount of power your panel needs to produce depends on the amount of sun exposure you expect on the shortest day of the year. In Canada, 80 Watt panels have been effective for ¾ of the year, but do not produce enough for continuous operation in the winter. For continuous winter operation, we have been recommending at least 150 Watts by industry experts. In the summer, 50 Watt panels have been sufficient.

#### Charge Controller

All solar panel setups require a charge controller. This is the device that mediates the power flow between the solar panel and the battery, keeping the panel from overcharging the battery, and ensuring electricity doesn’t flow into the panel at night when the panel voltage drops. We recommend getting a charge controller that also includes undervoltage protection, or ‘low-voltage cutoff’, to further protect the battery from getting overly drained by the receiver, or ‘load’. If your charge controller does not have undervoltage protection, a separate device should be used between the battery and load. See [undervoltage protection](power.md#undervoltage-protection) for more details.

The charge controller most often used by Birds Canadais the [MorningStar SunSaver SS-10L-12V](https://www.morningstarcorp.com/products/sunsaver/). This can charge a 12-volt battery with up to 10 Amps of current and includes a low-voltage cutoff. These have proven robust and longer-lasting than cheaper models, but they can still fail so it’s always important to have spares around.

