# Cogs⚙️
Cogs are the physical modules that build up the PedalPirat Ecosystem. They are connected via the [🔗Chain](https://github.com/PedalPirat/Chain), a mix of Bus and power that makes sure that all components can connect with each other.

## Overview
Every cog has one or multiple functions.
They can be either existing products or custom modules.

### Functions

#### 🏮 *Light* controller and modules
Lanterns are custom LED lights for Turn signals and brake indication, available lights (either connected via ANT+ or a custom module)
#### 🔧 *Actors* to control Shifters and other stuff
Actors that do something, be it controlling shifters like the Rohloff E-14 or the [HandleWarmer](https://github.com/PedalPirat/HandleWarmer)
#### 🔭 *Sensors* to gather data
Telescopes are sensors like the GPS Module or the [Quarq TyreWiz 2.0 Tyre Pressure Sensor](https://www.sram.com/de/quarq/models/wh-trwz-e1)
#### 🔋 *Power* Management
Power Controller for the System, controlling the Energy delivered by the [Forumslader](https://www.forumslader.de/aheadlader-v6/) or a connected Powerbank and also the charging of connected devices like a Phone or the [Mecha Comet](https://mecha.so/comet)
#### 🛞 *Inputs& from Buttons and other controls
Inputs like buttons and connectors for brake lever sensors like the [Magura MT5e](https://www.bike-components.de/de/Magura/MT5e-Carbotecture-Scheibenbremse-p45434/)


## Modules
### Custom
#### [Bridge](https://github.com/PedalPirat/comet-Navigator)
Central Micocontroller with Dock for a bike computer and a lot of Sensors
#### [HandleWarmer](https://github.com/PedalPirat/Cog-HandleWarmer)
Heated handlebar grips

#### Lights

### Existing
#### [SRAM/Quarq TyreWiz 2.0🔭](https://www.sram.com/de/quarq/models/wh-trwz-e1)
- Chain: ANT+, BTLE
- Power: Battery
- Function:
  - 🔭 Tyre Pressure
 
#### [SRAM/RockShox Reverb AXS XPLR](https://www.sram.com/de/rockshox/models/sp-rvb-xplr-a1)
- Chain: ANT+
- Power: Battery/ [Connection Cable](https://www.bike24.de/p1834215.html)
- Function
  - 🔧 Dropper Post
#### [Garmin Varia eRTL615](https://www.garmin.com/en-US/p/874099/)
- Chain: ANT+, BTLE
- Power: 12V
- Function
  - 🔭 Radar
  - 🏮 Light

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

#### [e2ip/STm EDGE AI Sensing Kit](https://shop.e2ip.com/)
- Chain: USB
- Power: USB
- Function
  - 🔭 Camera
