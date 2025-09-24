# SV08

Information and modifications relevant to the Sovol SV08

---
INDEX

<br/>

- [Comments and Critiques](#comments-and-critiques)
  - [Overall](#overall)
  - [Camera](#camera)
  - [Electronics](#electronics)
  - [Filament](#filament)
  - [Interface](#interface)
  - [Screen](#screen)
  - [Spool Holder](#spool-holder)
  - [Toolhead](#toolhead)

<br/>

- [Modifications](#modifications)
  - [Anti-Vibration Feet](#mod-anti-vibration-feet)
  - [Camera Angle](#mod-camera-angle)
  - [Corner Braces](#mod-corner-braces)
  - [Enclosure](#mod-enclosure)
  - [Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor)
  - [Filament Runout Sensor](#mod-filament-runout-sensor)
  - [Klipper Screen](#mod-klipper-screen)
  - [Mainline Klipper](#mod-mainline-klipper)
  - [Microswiss Hotend](#mod-microswiss-hotend)
  - [Multiple Spool Holder](#mod-multiple-spool-holder)
  - [Poop Bin Holder](#mod-poop-bin-holder)
  - [Power Inlet Connector](#mod-power-inlet-connector)
  - [Sovol Hotend Kit](#mod-sovol-hotend-kit)
  - [Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
  - [Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)
  - [Toolchanger System](#mod-toolchanger-system)
  - [USB Stick](#mod-usb-stick)

<br/>

- [Builds](#builds)
  - [FALCONER](#unit1--falconer)
  - [HYDRA](#unit2--hydra)
  - [STRIX](#unit3--strix)
  - [NACHTEULE](#unit4--nachteule)

---

# Comments and Critiques
A check in the box indicates there is at least one solution for the issue (or it isn't an issue if it's a bullet).

## Overall
- 001: the blue/anthracite color scheme is quite appealing (or at least not appalling).  The grey Comgrow version is actually nicer from a utilitarian point of view.
- [x] 002: a printable match to the main blue is elusive thus mods must be printed in a complementary color.  Similar for the grey - but that's less of an issue.
- [x] 003: the frame may be a bit wobbly.
- [x] 004: the printer may vibrate and move around a bit as well as shake the table.
- [x] 005: the stock printer cannot print ABS/ASA/etc.
- [x] 006: the stock system can only print one color.
- [x] 007: sometimes it is tough to align the build plate.
## Camera
- [x] 071: is mounted at a shallow angle not giving optimal view of the plate from its location.
## Electronics
- [x] 041: mcu_fan is (by default) always full on and it is noisy.
- 042: bay in base is protected with a formed sheet (GOOD).
- [x] 043: main board does not use mainline Klipper.
- [x] 044: USB stick failed on at least one machine within a month.
## Filament
- [ ] 061: path requires disassembling PTFE tube when filmament runs out (distance from sensor to toolhead is long so loading a follower is not reasonable).
- [x] 062: doesn't seem to flow through the nozzle consistently.
- [x] 063: can get tangled in stock spool holder ruining a print.
- [x] 064: is dumped in many places (front left, back left) - there is no trash can.
- [x] 065: sensor (apparently) randomly generates an error on Stepper Z1.  Unplugging it avoids the error but not having a filament sensor is archaic (barbaric?).
- [x] 066: runs out and the printer doesn't stop.
## Interface
- [ ] 021: for power inlet seems upside down - 1 is down while 0 is up.
- [x] 022: for power inlet causes cord to stick straight out thus unnecessarily distancing printer from the wall.
- [ ] 023: for power inlet should be on the same side as the spool holder and interface ports to minimize protrusions.
## Screen
- [ ] 031: (Klipper) is partially eclipsed by the printed case for sight and touch.
- [ ] 032: (Klipper) requires 2 separate cables that run externally.
- [x] 033: (Standard) is a bit klunky although functional.
- [ ] 034: (Standard) menu options are bare bones.
## Spool Holder
- [x] 011: is too free-wheeling.
- [x] 012: was broken and not fixable in one delivery - couldn't find a suitable adhesive.
- [x] 013: sticks out an an odd angle and is unnecessarily above the top surface.
- 014: is on the same side as the USB port (GOOD).
- [x] 015: sticks out far to the side because its diameter is at right angles to the side of the printer.
- [x] 016: only holds one spool
## Toolhead
- [ ] 051: is large and obscures view of nozzle interface to buildplate.
- [ ] 052: fan is noisy.
- [x] 053: board does not use mainline Klipper.
- [ ] 054: doesn't actually dip low enough to clean the nozzle on the brush.
- [ ] 055: intentially sets nozzle onto plate and squishes out filament before printing purge line which seems like a bad idea.  But maybe this is intentional to minimize nozzle oozing and help clean it?
- [ ] 056: is missing spring on tensioner screw.  In general, of the ~12 toolheads delivered, about half had missing parts.

---

# Modifications
A check in the box indicates it has been applied at least once.

## MOD: Anti-vibration Feet
- [x] [Shock and Noise Cancelling Washing Machine Support](https://a.co/d/hu0rnZA)
- [x] [SV08 Washing Machine Anti-Vibration Adapter](https://www.printables.com/model/1213029-sv08-washing-machine-anti-vibration-adapter) printed in TPU
- Address(es) 004 above
## MOD: Build Plate Alignment
- [ ] [SV08 Build Plate Alignment](https://www.printables.com/model/1111031-sv08-build-plate-alignment)
- Address(es) 007 above
## MOD: Camera Angle
- [ ] [Printables: Camera Angle Bracket](https://www.printables.com/model/912397-sovol-sv08-camera-angle-bracket)
- Address(es) 071 above
## MOD: Color of Mods
- [x] [Filabees ASA Sparkle Storm Gray](https://www.amazon.com/dp/B0D5LJHHL7)
- [x] [Bambu TPU for AMS in Blue](https://us.store.bambulab.com/products/tpu-for-ams?id=43059884654728) (this isn't fully TPU but the color is nice...)
- [x] [Geeetech TPU Clear](https://www.amazon.com/dp/B0C3TMQLC8)
- Address(es) 001,002 above
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
- [ ] [Sovol SV08 Filament Runout Sensor](https://www.sovol3d.com/collections/fdm-parts/products/filament-runout-sensor-kit-for-sv08) (stock)
- [ ] [BTT SFS](https://biqu.equipment/products/btt-sfs-v2-0-smart-filament-sensor)
- Address(es) 066 above
## MOD: Klipper Screen
- [x] [Sovol SV08 HDMI Capacitive Klipper Screen](https://www.sovol3d.com/collections/fdm-parts/products/sv08-upgraded-hdmi5-screen-kits)
- Address(es) 033 above
## MOD: Mainline Klipper
- [x] [github: SV08 Mainline Klipper](https://github.com/Rappetor/Sovol-SV08-Mainline/blob/main/README.md)
- Address(es) 043, 053 above
## MOD: Microswiss Hotend
- [x] [Microswiss FlowTech™ Hotend for Sovol SV08](https://store.micro-swiss.com/collections/all-metal-hotend-kits/products/microswiss-flowtech-hotend-for-sovol-sv08)
- Address(es) 062 above
## MOD: Multiple Spool Holder
- [ ] [Minimalist Spool Holder for 2020/2040 Extrusion](https://www.printables.com/model/504204-minimalist-spool-holder-for-20202040-extrusion)
- Address(es) 016 above
## MOD: Poop Bin Holder
- [ ] [Poop Bin for SV08](https://www.printables.com/model/1133022-poop-bin-for-sv08)
## MOD: Power Inlet Connector
- [x] C14 to C13 90&deg; connector [Amazon: purchased](https://a.co/d/5RM94Rs)
  - or [Amazon: search for options](https://www.amazon.com/s?k=C14+to+C13+90+degree+power+extension+adapter&i=electronics&crid=2Q3B6TUQFPUAM&sprefix=c14+to+c13+90+degree+power+extension+adapter%2Celectronics%2C81&ref=nb_sb_noss)
- Address(es) 022 above
## MOD: Spool Holder and Filament Runout Sensor
- [x] Side spool holder [Printables: Side Mount Spool Holder V2](https://www.printables.com/model/901288-sovol-sv08-side-mount-spool-holder-v2) (print in reverse for front right side)
- [x] Filament runout sensor holder [Printables: Filament Runout Sensor Mount](https://www.printables.com/model/919447-sv08-filament-runout-sensor-holder)
- Address(es) 011, 012, 013, 015, 016 above
## MOD: Sovol Hotend Kit
- [x] [Sovol Hardened Steel Nozzle Kit](https://www.sovol3d.com/collections/fdm-parts/products/0-4mm-hardened-steel-nozzle-kit-for-sv08-t300)
- Address(es) 062 above
## MOD: Temperature Controlled MCU Fan
- [x] [Printables: Silent Fan Mod](https://www.printables.com/model/936462-silent-fan-airflow-mod-for-sovol-sv08) or [YouTube- ThePrintasaurus](https://www.youtube.com/watch?v=HFTSZy99Qmo&t=139s)
- Address(es) 041 above
## MOD: Toolchanger System
- [ ] [Teaching Tech SVO8 Budget Toolchanger](https://www.youtube.com/playlist?list=PLGqRUdq5ULsNIN_40Bv1iTbElj6O7BRrU)
- Address(es) 006 above
## MOD: USB Stick
- [x] [64GB USB 3.0 Flash Drive](https://www.amazon.com/dp/B09MT9KXQ1) it's overkill but it's blue
- Address(es) 044 above

---

# Builds
A check in the box indicates this mod has been applied to the indicated unit.

## Unit1- FALCONER
Why FALCONER?  It is a translation of "sovol". Although the origin of SOVOL (as a company name) is not known, the world "sovol" translates to "owl" (Ukrainian/Czech) or "question" (Uzbek) but somewhere it was also mapped to "falconer" (link lost).  The owl is an obvious choice - especially given Sovol's alignment with Obico and their logo.  But, "falconer" is more in line with the Voron nomenclature.

Common Modifications
- [x] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet) (in Blue)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Color of Mods](#mod-color-of-mods)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT)
- [x] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [ ] [MOD: Poop Bin Holder](#mod-poop-bin-holder)
- [x] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [x] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [ ] [MOD: Enclosure](#mod-enclosure)
- [x] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (stock)
- [x] [MOD: Microswiss Hotend](#mod-microswiss-hotend)

## Unit2- HYDRA
Why HYDRA?  Say "ee-dra" (édra)...  Besides a wonderful destination in Greece, Hydra also alludes to a multi-headed monster which sounds like a good name for a toolchanger.  Thank Michael at [Teaching Tech](https://www.youtube.com/watch?v=7roEGbkvSCc&list=PLGqRUdq5ULsNIN_40Bv1iTbElj6O7BRrU) for this.

Common Modifications
- [x] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet) (in Blue)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Color of Mods](#mod-color-of-mods)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (BTT times 6)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT times 6)
- [ ] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [ ] [MOD: Poop Bin Holder](#mod-poop-bin-holder)
- [x] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [ ] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [x] [MOD: Sovol Hotend Kit](#mod-sovol-hotend-kit) (times 6)
- [ ] [MOD: Toolchanger System](#mod-toolchanger-system) (6 heads)
- [ ] [MOD: Multiple Spool Holder](#mod-multiple-spool-holder) (6 spools)

## Unit3- STRIX
- Why STRIX?  See FALCONER and the obvious link to owl.  This unit is actually labeled Comgrow and has grey parts (instead of the Sovol SV08 light blue).  STRIX is a genus of owls including S. nebulosa (but nebulosa doesn't sound as cool).  [Wikipedia Great Grey Owl](https://en.wikipedia.org/wiki/Great_grey_owl).

Common Modifications
- [x] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet) (in Clear)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Color of Mods](#mod-color-of-mods)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (BTT)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT)
- [ ] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [ ] [MOD: Poop Bin Holder](#mod-poop-bin-holder)
- [ ] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [ ] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [x] [MOD: Microswiss Hotend](#mod-microswiss-hotend)

## Unit3- STRIX
- Why STRIX?  See FALCONER and the obvious link to owl.  This unit is actually labeled Comgrow and has grey parts (instead of the Sovol SV08 light blue).  STRIX is a genus of owls including S. nebulosa (but nebulosa doesn't sound as cool).  [Wikipedia Great Grey Owl](https://en.wikipedia.org/wiki/Great_grey_owl).

Common Modifications
- [ ] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet) (in Clear)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Color of Mods](#mod-color-of-mods)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (BTT)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT)
- [ ] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [ ] [MOD: Poop Bin Holder](#mod-poop-bin-holder)
- [ ] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [ ] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [ ] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (BTT)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT)
- [x] [MOD: Microswiss Hotend](#mod-microswiss-hotend)

## Unit4- NACHTEULE
- Why NACHTEULE?  A trip to the German consulate while deliberating on this Comgrow unit may have influenced the choice of name as the coloring suggests night owl.

Common Modifications
- [x] [MOD: Anti-vibration Feet](#mod-anti-vibration-feet) (in Clear)
- [ ] [MOD: Camera Angle](#mod-camera-angle)
- [x] [MOD: Color of Mods](#mod-color-of-mods)
- [x] [MOD: Corner Braces](#mod-corner-braces)
- [ ] [MOD: Filament Runout Sensor](#mod-filament-runout-sensor) (BTT)
- [ ] [MOD: Filament Anti-Tangle Sensor](#mod-filament-anti-tangle-sensor) (BTT)
- [ ] [MOD: Mainline Klipper](#mod-mainline-klipper)
- [ ] [MOD: Poop Bin Holder](#mod-poop-bin-holder)
- [ ] [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [x] [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [ ] [MOD: Temperature Controlled MCU Fan](#mod-temperature-controlled-mcu-fan)

Unit Specific
- [x] [MOD: Microswiss Hotend](#mod-microswiss-hotend)

---

# Notes to Self
Ideas when modding a Voron or Delta (or any printer or related device)

## Note: Consolidate Protrusions
- Where possible, conslidate protrusions to keep distancing restrictions to a single side.
  - It's okay if they aren't grouped together (separate physical from high-voltage ports from low-voltage ports).
