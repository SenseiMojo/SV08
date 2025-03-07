# SV08

Information/Modifications relevant to the Sovol SV08

---
INDEX

<br/>

- [Comments and Critiques](#comments-and-critiques)
  - [Overall](#overall)
  - [Spool Holder](#spool-holder)
  - [Interface](#interface)
  - [Screen](#screen)
  - [Electronics](#electronics)
  - [Toolhead](#toolhead)
  - [Filament](#filament)

<br/>

- [Modifications](#modifications)
  - [Anti-Vibration Feet](#mod-anti-vibration-feet)
  - [Camera Angle](#mod-camera-angle)
  - [Corner Braces](#mod-corner-braces)
  - [Enclosure](#mod-enclosure)
  - [Filament Anti-Tangle Sensor](#mod-filament-anti-tangle)
  - [Filament Runout Sensor](#mod-filament-runout-sensor)
  - [Mainline Klipper](#mod-mainline-klipper)
  - [Microswiss Hotend](#mod-microswiss-hotend)
  - [Power Inlet Connector](#mod-power-inlet-connector)
  - [Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
  - [Sovol Hotend Kit](#mod-sovol-hotend-kit)
  - [Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)
  - [Toolchanger System](#mod-toolchanger-system)

<br/>

- [Builds](#builds)
  - [FALCONER](#unit1--falconer)
  - [HYDRA](#unit2--hydra)
  - [STRIX](#unit3--strix)

---

# Comments and Critiques
A check in the box indicates there is at least one solution for the issue (or it isn't an issue if it's a bullet).

## Overall
- 001: the blue/anthracite color scheme is quite appealing (or at least not appalling).  The grey Comgrow version is actually nicer from a utilitarian point of view.
- [ ] 002: a printable match to the main blue is elusive thus mods must be printed in a complementary color.  Similar for the grey - but that's less of an issue.
- [x] 003: the frame may be a bit wobbly.
- [x] 004: the printer may vibrate and move around a bit as well as shake the table.
- [x] 005: the printer cannot print ABS/ASA/etc.
- [x] 006: the system can only print one color.
## Spool Holder
- [x] 011: is too free-wheeling.
- [x] 012: was broken and not fixable in one delivery - couldn't find a suitable adhesive.
- [x] 013: sticks out an an odd angle and is unnecessarily above the top.
- 014: is on the same side as the USB port (GOOD).
- [x] 015: sticks out far to the side.
## Interface
- [ ] 021: for power inlet seems upside down - 1 is down while 0 is up.
- [x] 022: for power inlet causes cord to stick straight out thus distancing printer from the wall.
- [ ] 023: for power inlet should be on the same side as the spool holder and interface ports to minimize protrusions.
## Screen
- [ ] 031: (Klipper) is partially eclipsed by the printed case for sight and touch.
- [ ] 032: (Klipper) requires 2 separate cables that run externally.
- [x] 033: (Standard) is a bit klunky although functional.
- [ ] 034: (Stamdard) menu options are bare bones.
## Electronics
- [x] 041: mcu_fan is full on and noisy.
- 042: bay in base is protected with a formed sheet (GOOD).
- [x] 043: main board does not use mainline Klipper.
## Toolhead
- [ ] 051: is large and obscures view of nozzle interface to buildplate.
- [ ] 052: fan is noisy.
- [x] 053: board does not use mainline Klipper.
- [ ] 054: doesn't actually dip low enough to clean the nozzle on the brush.
- [ ] 055: intentially sets nozzle onto plate and squishes out filament before printing purge line which seems like a bad idea.  But maybe this is to minimize nozzle oozing?
- [ ] 056: is missing spring on tensioner screw.
## Filament
- [ ] 061: path requires disassembling PTFE tube when filmament runs out (distance from sensor to toolhead is long so loading a follower is not reasonable).
- [x] 062: doesn't seem to flow through the nozzle consistently.
- [x] 063: can get tangled in spool holder ruining a print.
- [ ] 064: is dumped in many places (front left, back left) - there is no trash can.
- [x] 065: sensor (apparently) randomly generates an error on Stepper Z1.  Unplugging it avoids the error but not having a filament sensor is archaic (barbaric?).
## Camera
- [x] 071: is mounted at a shallow angle not giving optimal view of the plate from its location.

---

# Modifications
A check in the box indicates it has been applied at least once.

## MOD: Anti-vibration Feet
- [x] [Shock and Noise Cancelling Washing Machine Support](https://a.co/d/hu0rnZA)
- [x] [SV08 Washing Machine Anti-Vibration Adapter](https://www.printables.com/model/1213029-sv08-washing-machine-anti-vibration-adapter) printed in TPU
- Address(es) 004 above
## MOD: Camera Angle
- [ ] [Printables: Camera Angle Bracket](https://www.printables.com/model/912397-sovol-sv08-camera-angle-bracket)
- Address(es) 071 above
## MOD: Corner Braces
- [x] [Printables: Top Corner Braces](https://www.printables.com/model/978613-sovol-sv08-top-corner-braces)
- Address(es) 003 above
## MOD: Enclosure
- [ ] [Sovol SV08 Enclosure](https://www.sovol3d.com/collections/fdm-parts/products/sv08-transparent-plexiglass-open-enclosure)
- Address(es) 005 above
## MOD: Filament Anti-Tangle Sensor
- [x] [Sovol SV08 Filament Anti-Tangle Detector](https://www.sovol3d.com/collections/fdm-parts/products/sv08-filament-anti-tangle-detection-module)
- [ ] [BTT SFS](https://biqu.equipment/products/btt-sfs-v2-0-smart-filament-sensor)
- Address(es) 063 above
## MOD: Filament Runout Sensor
- [x] [Sovol SV08 Filament Runout Sensor](https://www.sovol3d.com/collections/fdm-parts/products/filament-runout-sensor-kit-for-sv08) (stock)
- [ ] [BTT SFS](https://biqu.equipment/products/btt-sfs-v2-0-smart-filament-sensor)
## MOD: Klipper Screen
- [x] [Sovol SV08 HDMI Capacitive Klipper Screen](https://www.sovol3d.com/collections/fdm-parts/products/sv08-upgraded-hdmi5-screen-kits)
- Address(es) 033 above
## MOD: Mainline Klipper
- [x] [github: SV08 Mainline Klipper](https://github.com/Rappetor/Sovol-SV08-Mainline/blob/main/README.md)
- Address(es) 043, 053 above
## MOD: Microswiss Hotend
- [x] [Microswiss FlowTech™ Hotend for Sovol SV08](https://store.micro-swiss.com/collections/all-metal-hotend-kits/products/microswiss-flowtech-hotend-for-sovol-sv08)
- Address(es) 062 above
## MOD: Power Inlet Connector
- [x] C14 to C13 90&deg; connector [Amazon: purchased](https://a.co/d/5RM94Rs)
  - or [Amazon: search for options](https://www.amazon.com/s?k=C14+to+C13+90+degree+power+extension+adapter&i=electronics&crid=2Q3B6TUQFPUAM&sprefix=c14+to+c13+90+degree+power+extension+adapter%2Celectronics%2C81&ref=nb_sb_noss)
- Address(es) 022 above
## MOD: Spool Holder and Filament Runout Sensor
- [x] Side spool holder [Printables: Side Mount Spool Holder V2](https://www.printables.com/model/901288-sovol-sv08-side-mount-spool-holder-v2)
- [x] Filament runout sensor holder [Printables: Filament Runout Sensor Mount](https://www.printables.com/model/919447-sv08-filament-runout-sensor-holder)
- Address(es) 011, 012, 013, 015 above
## MOD: Sovol Hotend Kit
- [x] [Sovol Hardened Steel Nozzle Kit](https://www.sovol3d.com/collections/fdm-parts/products/0-4mm-hardened-steel-nozzle-kit-for-sv08-t300)
- Address(es) 062 above
## MOD: Temperature Controlled MCU Fan
- [x] [Printables: Silent Fan Mod](https://www.printables.com/model/936462-silent-fan-airflow-mod-for-sovol-sv08) or [YouTube- ThePrintasaurus](https://www.youtube.com/watch?v=HFTSZy99Qmo&t=139s)
- Address(es) 041 above
## MOD: Toolchanger System
- [ ] [Teaching Tech SVO8 Budget Toolchanger](https://www.youtube.com/playlist?list=PLGqRUdq5ULsNIN_40Bv1iTbElj6O7BRrU)
- Address(es) 006 above

---

# Builds

## Unit1- FALCONER
Why FALCONER?  It is a translation of "sovol". Although the origin of SOVOL (as a company name) is not known, the world "sovol" translates to "owl" (Ukrainian/Czech) or "question" (Uzbek) but somewhere it was also mapped to "falconer" (link lost).  The owl is an obvious choice - especially given Sovol's alignment with Obico and their logo.  But, "falconer" is more in line with the Voron nomenclature.

Common Modifications
- [x] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (BTT to be installed)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT to be installed)
- [x] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [x] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [x] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [ ] [MOD: Enclosure](#mod-enclosure) (to be installed)
- [x] [MOD: Microswiss Hotend](#mod-microswiss-hotend)

## Unit2- HYDRA
Why HYDRA?  Say "ee-dra" (édra)...  Besides a wonderful destination in Greece, Hydra also alludes to a multi-headed monster which sounds like a good name for a toolchanger.  Thank Michael at [Teaching Tech](https://www.youtube.com/watch?v=7roEGbkvSCc&list=PLGqRUdq5ULsNIN_40Bv1iTbElj6O7BRrU) for this.

- [x] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (BTT to be installed)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT to be installed)
- [ ] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [x] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [ ] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [x] [MOD: Sovol Hotend Kit](#mod-sovol-hotend-kit)
- [ ] [MOD: Toolchanger System](#mod-toolchanger-system) (6 heads)

## Unit3- STRIX
- Why STRIX?  See FALCONER and the obvious link to owl.  This unit is actually labeled Comgrow and has grey parts (instead of the Sovol SV08 blue).  STRIX is a genus of owls including S. nebulosa (but nebulosa doesn't sound as cool).  [Wikipedia Great Grey Owl](https://en.wikipedia.org/wiki/Great_grey_owl).

- [ ] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [ ] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (BTT to be installed)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT to be installed)
- [ ] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [ ] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [ ] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [ ] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [ ] [MOD: Sovol Hotend Kit](#mod-sovol-hotend-kit)

## Unit4- TBA
- To Be Acquired

---

# Notes to Self
Ideas when modding a Voron or Delta (or any printer or related device)

## Note: Consolidate Protrusions
- Where possible, conslidate protrusions to keep distancing restrictions to a single side.
  - It's okay if they aren't grouped together (separate physical from high-voltage ports from low-voltage ports).
