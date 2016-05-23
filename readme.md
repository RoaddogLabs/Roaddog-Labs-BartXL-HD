## Roaddog Labs Bart Pro XL
## 
This is the Roaddog Bart XL 3D printer. This machine is a larger build
based on a mashup implemented from several designs including original
designs.  

####This machine is available in two variants

#####Bart Pro XL-LC is a lower cost version and a good upgrade platform for those with a Prusa i3 or Rework i3 variant to upgrade to a better frame and larger build area.  The LC variant uses M8 X and Z smooth rods and M5 threaded rod for the Z drive screw.  The LC uses Rework i3 printed parts.

The Bart Pro XL-LC version is frozen.  The current version is the Bart Pro XL-HD.  There will be no more work on this version but feel free to fork it and do with it as you wish.

#####Bart Pro XL-HD uses high performance lead screws, M10 precision shaft on all axis, high temp hot end suitable to 400*C, auto bed probe (bed leveling), silcone bed heater, MIC 6 precision aluminum print surface with PEI.

### This is a pre release version
### 
The current version is a pre release.  While the machine is functional
and works well, it's still very much a work in progress.  A set of pre release docs are at http://roaddoglabs.io/wiki/Roaddog_Labs_Bart_Pro_XL

Pull requests are welcome and encouraged.

#### Roaddog Labs Bart Pro XL-HD Specs ####


| Feature | Bart Pro XL-HD |
|---------|-------------|
| Base and Frame | Full melamine frame, printed parts, latest design for maximum stability and print speeds |
| Build Envelope | 360 mm x 240 mm x 200 mm |
| Resolution (printable layer thickness) | low res .3 mm; normal res .2 mm; hi res .1 mm; extra hi res .06 mm |
| Filament Diameter | 1.75 |
| Max Printing Temp | 248&#176; C with E3D Lite v6; 300&#176; C with E3D full v6 with thermistor, 400&#176; C with optional thermocouple |
| Compatible Materials | With E3D v6, any printable material to 400&#176; C with E3D v6 and thermocouple.  With E3D Lite v6 more than 15 types including PLA, ABS, Laywoo-D, HIPS, carbon fiber reinforced PLA, flexible filament, conductive PLA |
| Nozzle Size | .4 mm standard, user upgradable to a variety of sizes |
| Heated Bed | Polyimide heater, 24 volt with aluminum heat spreader |
| Print Surface |0.125" 6061-T6 aluminum |
| Extruder | Bart Direct Drive MK7, low profile, reduced weight and mass, optional E3D Titan or Bondtech QR extruder |
| Bed Tilt Compensation | Belt tilt compensation, also called auto bed leveling or tramming via an inductive sensor |
|Electronics | Mini Rambo configured for Bart Pro XL with Marlin firmware |
| Power Supply | 24 volts, 400 watts compact form factor |
| X Axis Motion | GT2 belt and pulley;  10 mm precision  bearings and chromed, hardened rods |
| Y Axis Motion | GT2 belt and pulley;  10 mm precision  bearings and chromed, hardened rods |
| Z Axis Motion | TR8 precision lead screw and nut; 10 mm precision bearings and chromed, hardened rods |
| Average Speeds | 100 mm/s (stock extruder, perimeters based on average tune) |
| Machine Footprint | 512 mm x 470 mm x 400 mm |
| Display/SD Card Reader | Full graphic LCD display and SD card reader for standalone operation |
| Optional Wireless and Print Server | User installed optional printing over Wifi and dedicated print server using Octoprint and a Raspberry Pi |

####License and Credits

Original designs from Roaddog Labs Ltd are released per the
Open Source Hardware Association guidelines for open source hardware at
http://www.oshwa.org/definition/.

Material specific to the Bart components and documentation that is not
derived from other sources are released under the Creative Commons
Attribution 4.0 International license.

Where applicable, the license of any derived work will be posted as
well.

The original Prusa i3 single plate files
(https://github.com/josefprusa/Prusa3) from Josef Prusa licensed under
GPL v3.

The original i3 Rework
(https://github.com/eMotion-Tech/Prusai3_EINSTEIN_Reworked) printed
parts files from eMotion-Tech are released under GPL 2.0.

The original i3 Hephestos files
(https://github.com/bq/prusa-i3-hephestos/) from bq Department of
Innovation and Robotics are licensed under Creative Commons Attribution
4.0 Sharealike International.

The Graber i3(https://github.com/sgraber/Graber) is licensed under GPL
v3.0.

The original modified i3 X idler with adjustable belt tensioner from
ramkam (http://www.thingiverse.com/thing:393870) licensed under Creative
Commons Atribution-Sharealike, no version stated.

Marlin firmware (https://github.com/MarlinFirmware/Marlin) from Erik van
der Zalm licensed under GPL, no version stated.


The original direct drive extruder for Wilson/i3
(http://www.thingiverse.com/thing:501755) from mrice licensed under
Creative Commons Attribution- Share Alike license, no version stated.