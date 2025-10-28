# Cogs⚙️
Cogs are the physical modules that build up the PedalPirat Ecosystem. They are connected via the [🔗Chain](https://github.com/PedalPirat/Chain), a mix of Bus and power that makes sure that all components can connect with each other.

## Overview
Every cog has one or multiple functions.
They can be either existing products or custom modules.

### Functions

#### [🏮Lantern](https://github.com/PedalPirat/Lantern) - Light controller and modules
Lanterns are custom LED lights for Turn signals and brake indication, available lights (either connected via ANT+ or a custom module)
#### [🔧Rudder](https://github.com/PedalPirat/Rudder) - Actors to control Shifters and other stuff
Rudders are actors that do something, be it controlling shifters like the Rohloff E-14 or the [HandleWarmer](https://github.com/PedalPirat/HandleWarmer)
#### [🔭Telescope](https://github.com/PedalPirat/Telescope) - Sensors to gather data
Telescopes are sensors like the GPS Module or the [Quarq TyreWiz 2.0 Tyre Pressure Sensor](https://www.sram.com/de/quarq/models/wh-trwz-e1)
#### [🔋PowderKeg](https://github.com/PedalPirat/PowderKeg) - Power Management
The PowederKeg is the Power Controller for the System, controlling the Energy delivered by the [Forumslader](https://www.forumslader.de/aheadlader-v6/) or a connected Powerbank and also the charging of connected devices like a Phone or the [Mecha Comet](https://mecha.so/comet)
#### [🛞Tiller](https://github.com/PedalPirat/Tiller) - Input Buttons and other controls
Inputs like buttons and connectors for brake lever sensors like the [Magura MT5e](https://www.bike-components.de/de/Magura/MT5e-Carbotecture-Scheibenbremse-p45434/)


## Modules
### Custom
### Existing
#### [SRAM/Quarq TyreWiz 2.0🔭](https://www.sram.com/de/quarq/models/wh-trwz-e1)
- Chain: ANT+, BTLE
- Power: Battery
- Function:
  - 🔭 Tyre Pressure
  - 
#### [Garmin Varia eRTL615](https://www.garmin.com/en-US/p/874099/)
- Chain: ANT+, BTLE
- Power: 12V
- Function
  - 🔭 Radar
  - 🏮 Light
  - 
#### [Bikone BB Torque Sensor](https://www.bikone.com/bottombracket-torque-sensors/)
- Chain: CAN
- Power: 12V
- Function
  - 🔭 Power
  - 🔭 Crank Position
 
#### [Magene AT1600](https://www.magene.com/en/bike-lights/208-at1200-at1600-smart-bike-headlight.html)
- Chain: ANT+, USB
- Power: USB-PD
- Function
  - 🏮 Light
  - 🔋 Powerbank
