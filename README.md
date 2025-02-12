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
  - [Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
  - [Power Inlet Connector](#mod-power-inlet-connector)
  - [Corner Braces](#mod-corner-braces)
  - [Microswiss Hotend](#mod-microswiss-hotend)
  - [Sovol Hotend Kit](#mod-sovol-hotend-kit)
- [Builds](#builds)
  - [Falconer](#falconer)
  - [Hydra](#hydra)

---

# Comments and Critiques
## Overall
- 001: the blue/anthracite color scheme is quite appealing (or at least not appalling).
- [ ] 002: a printable match to the main blue is elusive thus mods must be printed in a complementary color.
- [x] 003: the frame may be a bit wobbly.
- [x] 004: the printer may vibrate and move around a bit as well as shake the table.
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
- [ ] 041: mcu_fan is full on and noisy.
- [ ] 042: bay in base is protected with a formed sheet (GOOD).
- [ ] 043: mainboard does not use mainline Klipper.
## Toolhead
- [ ] 051: is large and obscures view of nozzle interface to buildplate.
- [ ] 052: fan is noisy.
- [ ] 053: board does not use mainline Klipper.
## Filament
- [ ] 061: path requires disassembling PTFE tube when filmament runs out (distance from sensor to toolhead is long so loading a follower is not reasonable).
- [ ] 062: doesn't seem to flow through the nozzle consistently.
## Camera
- [ ] 071: is mounted at a shallow angle not giving optimal view of the plate from its location.

---

# Modifications
## MOD: Mainline Klipper
- [ ] [github: SV08 Mainline Klipper](https://github.com/Rappetor/Sovol-SV08-Mainline/blob/main/README.md)
- Address(es) 043 above
## MOD: Spool Holder and Filament Runout Sensor
- [ ] Side spool holder [Printables: Side Mount Spool Holder V2](https://www.printables.com/model/901288-sovol-sv08-side-mount-spool-holder-v2)
- Address(es) 011, 012, 013, 014, 015 above
- [ ] Filament runout sensor holder [Printables: Filament Runout Sensor Mount](https://www.printables.com/model/919447-sv08-filament-runout-sensor-holder)
- Supports mod above
## MOD: Power Inlet Connector
- [ ] C14 to C13 90&deg; connector [Amazon: purchased](https://a.co/d/5RM94Rs)
  - or [Amazon: search for options](https://www.amazon.com/s?k=C14+to+C13+90+degree+power+extension+adapter&i=electronics&crid=2Q3B6TUQFPUAM&sprefix=c14+to+c13+90+degree+power+extension+adapter%2Celectronics%2C81&ref=nb_sb_noss)
- Address(es) 022 above
## MOD: Corner Braces
- [ ] [Printables: Top Corner Braces](https://www.printables.com/model/978613-sovol-sv08-top-corner-braces)
- Address(es) 003 above
## MOD: Microswiss Hotend
- [ ] [Microswiss FlowTech™ Hotend for Sovol SV08](https://store.micro-swiss.com/collections/all-metal-hotend-kits/products/microswiss-flowtech-hotend-for-sovol-sv08)
## MOD: Sovol Hotend Kit
- [ ] [Sovol Hardened Steel Nozzle Kit](https://www.sovol3d.com/collections/fdm-parts/products/0-4mm-hardened-steel-nozzle-kit-for-sv08-t300)
## MOD: Anti-vibration Feet
- [ ] [Shock and Noise Cancelling Washing Machine Support](https://a.co/d/hu0rnZA)
- [ ] [Anti-Vibration Washing Machine Adapter](https://makerworld.com/en/models/20891#profileId-23767) printed in TPU
- [ ] upload adapter (TO DO)
- Address(es) 004 above

---

# Builds
## Falconer
- [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [MOD: Corner Braces](#mod-corner-braces)
- [MOD: Anti-vibration Feet](#mod-anti-vibration-feet)
- [MOD: Microswiss Hotend](#mod-microswiss-hotend)

## Hydra
- [MOD: Spool Holder and Filament Runout Sensor](#mod-spool-holder-and-filament-runout-sensor)
- [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [MOD: Corner Braces](#mod-corner-braces)
- [MOD: Anti-vibration Feet](#mod-anti-vibration-feet)
- [MOD: Sovol Hotend Kit](#mod-sovol-hotend-kit)

## Unit3 (to be acquired)

## Unit4 (to be acquired)

---

# Notes to Self
Ideas when modding a Voron or Delta (or any printer or related device)

## Note: Consolidate Protrusions
- Where possible, conslidate protrusions to keep distancing restrictions to a single side.
  - It's okay if they aren't grouped together (separate high- from low- voltage).
