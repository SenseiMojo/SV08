# SV08
Information/Modifications relevant to the Sovol SV08

---

INDEX
- [Comments and Critiques](#comments-and-critiques)
  - [Overall](#overall)
  - [Spool Holder](#spool-holder)
  - [Interface](#interface)
  - [Klipper Screen](#klipper-screen)
  - [Electronics](#electronics)
  - [Toolhead](#toolhead)
  - [Filament](#filament)
- [Modifications](#modifications)
  - [Anti-Vibration Feet](#mod-anti-vibration-feet)
  - [Camera Angle](#mod-camera-angle)
  - [Corner Braces](#mod-corner-braces)
  - [Enclosure](#mod-enclosure)
  - [Filament Sensor](#mod-filament-sensor)
  - [Mainline Klipper](#mod-mainline-klipper)
  - [Microswiss Hotend](#mod-microswiss-hotend)
  - [Power Inlet Connector](#mod-power-inlet-connector)
  - [Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
  - [Sovol Hotend Kit](#mod-sovol-hotend-kit)
  - [Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)
  - [Toolchanger System](#mod-toolchanger-system)
- [Builds](#builds)
  - [Falconer](#unit1--falconer)
  - [Hydra](#unit2--hydra)

---

# Comments and Critiques
## Overall
- 001: the blue/anthracite color scheme is quite appealing (or at least not appalling).
- [ ] 002: a printable match to the main blue is elusive thus mods must be printed in a complementary color.
- [x] 003: the frame may be a bit wobbly.
- [x] 004: the printer may vibrate and move around a bit as well as shake the table.
- [x] 005: the printer cannot print ABS/ASA/etc.
- [x] 006: the system can only print one color.
## Spool Holder
- [x] 011: is too free-wheeling.
- [x] 012: was broken and not fixable in one delivery - couldn't find a suitable adhesive.
- [x] 013: sticks out an an odd angle.
- 014: is on the same side as the USB port (GOOD).
- [x] 015: sticks out far to the side.
## Interface
- [ ] 021: for power inlet seems upside down - 1 is down while 0 is up.
- [x] 022: for power inlet causes cord to stick straight out thus distancing printer from the wall.
- [ ] 023: for power inlet should be on the same side as the spool holder and interface ports to minimize protrusions.
## Klipper Screen
- [ ] 031: is partially eclipsed by the printed case for sight and touch.
- [ ] 032: requires 2 separate cables that run externally.
## Electronics
- [x] 041: mcu_fan is full on and noisy.
- 042: bay in base is protected with a formed sheet (GOOD).
- [x] 043: main board does not use mainline Klipper.
## Toolhead
- [ ] 051: is large and obscures view of nozzle interface to buildplate.
- [ ] 052: fan is noisy.
- [x] 053: board does not use mainline Klipper.
## Filament
- [ ] 061: path requires disassembling PTFE tube when filmament runs out (distance from sensor to toolhead is long so loading a follower is not reasonable).
- [x] 062: doesn't seem to flow through the nozzle consistently.
- [x] 063: can get tangled in spool holder ruining a print.
## Camera
- [ ] 071: is mounted at a shallow angle not giving optimal view of the plate from its location.

---

# Modifications
## MOD: Anti-vibration Feet
- [ ] [Shock and Noise Cancelling Washing Machine Support](https://a.co/d/hu0rnZA)
- [ ] [Anti-Vibration Washing Machine Adapter](https://makerworld.com/en/models/20891#profileId-23767) printed in TPU
- [ ] upload adapter (TO DO)
- Address(es) 004 above
## MOD: Camera Angle
- [ ] [Printables: Camera Angle Bracket](https://www.printables.com/model/912397-sovol-sv08-camera-angle-bracket)
- Address(es) 071 above
## MOD: Corner Braces
- [ ] [Printables: Top Corner Braces](https://www.printables.com/model/978613-sovol-sv08-top-corner-braces)
- Address(es) 003 above
## MOD: Enclosure
- [ ] [Sovol SV08 Enclosure](https://www.sovol3d.com/collections/fdm-parts/products/sv08-transparent-plexiglass-open-enclosure)
- Address(es) 005 above
## MOD: Filament Sensor
- [ ] [Sovol SV08 Filament Anti-Tangle Detector](https://www.sovol3d.com/collections/fdm-parts/products/sv08-filament-anti-tangle-detection-module)
- Address(es) 063 above
## MOD: Mainline Klipper
- [ ] [github: SV08 Mainline Klipper](https://github.com/Rappetor/Sovol-SV08-Mainline/blob/main/README.md)
- Address(es) 043, 053 above
## MOD: Microswiss Hotend
- [ ] [Microswiss FlowTech™ Hotend for Sovol SV08](https://store.micro-swiss.com/collections/all-metal-hotend-kits/products/microswiss-flowtech-hotend-for-sovol-sv08)
- Address(es) 062 above
## MOD: Power Inlet Connector
- [ ] C14 to C13 90&deg; connector [Amazon: purchased](https://a.co/d/5RM94Rs)
  - or [Amazon: search for options](https://www.amazon.com/s?k=C14+to+C13+90+degree+power+extension+adapter&i=electronics&crid=2Q3B6TUQFPUAM&sprefix=c14+to+c13+90+degree+power+extension+adapter%2Celectronics%2C81&ref=nb_sb_noss)
- Address(es) 022 above
## MOD: Spool Holder and Filament Runout Sensor
- [ ] Side spool holder [Printables: Side Mount Spool Holder V2](https://www.printables.com/model/901288-sovol-sv08-side-mount-spool-holder-v2)
- [ ] Filament runout sensor holder [Printables: Filament Runout Sensor Mount](https://www.printables.com/model/919447-sv08-filament-runout-sensor-holder)
- Address(es) 011, 012, 013, 015 above
## MOD: Sovol Hotend Kit
- [ ] [Sovol Hardened Steel Nozzle Kit](https://www.sovol3d.com/collections/fdm-parts/products/0-4mm-hardened-steel-nozzle-kit-for-sv08-t300)
- Address(es) 062 above
## MOD: Temperature Controlled MCU Fan
- [ ] [Printables: Silent Fan Mod](https://www.printables.com/model/936462-silent-fan-airflow-mod-for-sovol-sv08) or [YouTube- ThePrintasaurus](https://www.youtube.com/watch?v=HFTSZy99Qmo&t=139s)
- Address(es) 041 above
## MOD: Toolchanger System
- [ ] [Teaching Tech SVO8 Budget Toolchanger](https://www.youtube.com/playlist?list=PLGqRUdq5ULsNIN_40Bv1iTbElj6O7BRrU)
- Address(es) 006 above

---

# Builds

## Unit1- Falconer
- [x] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Sensor](#mod-filament-sensor) (to be installed)
- [x] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [x] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [x] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [ ] [MOD: Enclosure](#mod-enclosure) (to be installed)
- [x] [MOD: Microswiss Hotend](#mod-microswiss-hotend)

## Unit2- Hydra
- [x] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Sensor](#mod-filament-sensor) (to be installed)
- [ ] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [x] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [ ] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [x] [MOD: Sovol Hotend Kit](#mod-sovol-hotend-kit)
- [ ] [MOD: Toolchanger System](#mod-toolchanger-system) (6 heads)

## Unit3- TBA
- To Be Acquired

## Unit4- TBA
- To Be Acquired

---

# Notes to Self
Ideas when modding a Voron or Delta (or any printer or related device)

## Note: Consolidate Protrusions
- Where possible, conslidate protrusions to keep distancing restrictions to a single side.
  - It's okay if they aren't grouped together (separate physical from high-voltage ports from low-voltage ports).
