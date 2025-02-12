# SV08
Information &amp; Modifications relevant to the Sovol SV08

---
INDEX
- [Comments and Critiques](#comments-and-critiques)
  - [Overall](#overall)
  - [Spool Holder](#spool-holder)
  - [Interface](#interface)
  - [Klipper Screen](#klipper-screen)
  - [Electronics Compartment](#electronics-compartment)
  - [Toolhead](#toolhead)
  - [Filament Path](#filament-path)
- [Modifications](#modifications)
  - [Spool Holder](#mod-spool-holder)
  - [Power Inlet Connector](#mod-power-inlet-connector)
- [Builds](#builds)
  - [Falconer](#falconer)
  - [Hydra](#hydra)

---

# Comments and Critiques
---
## Overall
- 001: the color scheme is appealing.
- 002: a printable match to the main blue is elusive.
- 003: the frame may be a bit wobbly.
## Spool Holder
- [ ] 011: is too free-wheeling.
- [ ] 012: was broken and not fixable in one delivery - couldn't find a suitable adhesive.
- [ ] 013: sticks out an an odd angle.
- 014: is on the same side as the USB port (GOOD).
- [ ] 015: sticks out far to the side.
## Interface
- 021: for power inlet seems upside down - 1 is down while 0 is up.
- [ ] 022: for power inlet causes cord to stick straight out thus distancing printer from the wall.
- 023: for power inlet should be on the same side as the spool holder and interface ports to minimize protrusions.
## Klipper Screen
- 031: is partially eclipsed by the printed case for sight and touch.
- 032: requires 2 separate cables that run externally.
## Electronics Compartment
- 041: mcu_fan is full on and noisy.
- 042: is protected with a formed sheet (GOOD).
## Toolhead
- 051: is large and obscures view of nozzle interface to buildplate.
- 052: fan is noisy.
## Filament Path
- 061: requires disassembling PTFE tube when filmament runs out (distance from sensor to toolhead is long so loading a follower is not reasonable).

# Modifications
---
## MOD: Spool Holder
- Side spool holder and filament runout sensor holder
  - [Side Mount Spool Holder V2](https://www.printables.com/model/901288-sovol-sv08-side-mount-spool-holder-v2)
  - [Filament Runout Sensor Mount](https://www.printables.com/model/919447-sv08-filament-runout-sensor-holder)
  - Address(es) 011, 012, 013, 014, 015 above
## MOD: Power Inlet Connector
- C14 to C13 90&deg; connector
  - [purchased](https://a.co/d/5RM94Rs)
  - or [search for options](https://www.amazon.com/s?k=C14+to+C13+90+degree+power+extension+adapter&i=electronics&crid=2Q3B6TUQFPUAM&sprefix=c14+to+c13+90+degree+power+extension+adapter%2Celectronics%2C81&ref=nb_sb_noss)
  - Address(es) 022 above
## MOD: Top Corner Braces
- [Time Corner Braces](https://www.printables.com/model/978613-sovol-sv08-top-corner-braces)
  - Address(es) 003 above
 
# Builds
## Falconer
- [MOD: Spool Holder](#mod-spool-holder)
- [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [MOD: Top Corner Braces](#mod-top-corner-braces)

## Hydra
- [MOD: Spool Holder](#mod-spool-holder)
- [MOD: Power Inlet Connector](#mod-power-inlet-connector)
- [MOD: Top Corner Braces](#mod-top-corner-braces)

 <hr/>
# Note to Self
Ideas when modding a Voron or Delta (or any printer or related device)

## Note: Consolidate Protrusions
- Where possible, conslidate protrusions to keep distancing restrictions to a single side
