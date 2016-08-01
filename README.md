hw-altas-node
================

This is a minimal node PCB for the DecaWave DWM1000 module.
The main MCU is a LPC1347.

Project schematic:
![Top](docu/schematic.png "Top")

The PCB is designed to fit in a 1551G series Hammond case.

## BOM
| Identifier | Type/Value | Quantity | Supplier Id | Supplier | Comment |
| ---        | ---        | ---      | ---         | ---      | ---     |
| R1, R2 | 33 Ω | 2 | SMD-0603 33  | [Reichelt][reichelt] |
| R10-R14 | 470 Ω | 5 | SMD-0603 470 | [Reichelt][reichelt] |
| R3, R5, R6 | 1 kΩ | 3 | SMD-0603 1K5 | [Reichelt][reichelt] |
| R4, R7, R9 | 10 kΩ | 3 | SMD-0603 10K | [Reichelt][reichelt] |
| R8 | 100 kΩ | 1 | SMD-0603 100K | [Reichelt][reichelt] |
| C1, C2 | 18 pF | 2 | NPO-G0603 18P | [Reichelt][reichelt] |
| C7, C3 | 10 nF | 2 | X7R-G0603 10N | [Reichelt][reichelt] |
| C3, C4, C8, C9, C10 | 100 nF | 5 | X7R-G0603 100N | [Reichelt][reichelt] |
| C5, C6, C11 | 10 µF | 3 | X5R-G0603 10/6 | [Reichelt][reichelt] |
| L1 | Ferrite Bead | 1 | BLM18AG 121 | [Reichelt][reichelt] |
| Y1 | 12 MHz | 1 | 12,000000-MT | [Reichelt][reichelt] |
| Q1 | BC807 | 1 | BC 807-16 SMD | [Reichelt][reichelt] |
| LED_SYS | LED white | 1 | LW L283 | [Reichelt][reichelt] |
| LED_TX | LED red | 1 | LS L29K | [Reichelt][reichelt] |
| LED_RX | LED orange | 1 | LO L29K | [Reichelt][reichelt] |
| IC1 | LPC1347 TQFP-48 | 1 | 771-LPC1347FBD48,151 | [Mouser][mouser] |
| IC2 | MCP1755 | 1 | MCP 1755T-3302EO | [Reichelt][reichelt] |
| IC3 | DWM1000 | 1 | 1479-1002-1-ND | [Digikey][digikey] |
| IC4 | MPU-9250 | 1 | 1428-1019-1-ND | [Digikey][digikey] |
| X1S | USB Jack | 1 | USB BWM SMD | [Reichelt][reichelt] |
| JP3 | 2x5 1.27 | 1 | 649-202112100010C4LF | [Mouser][mouser] |
| SW1 | Tact Switch | 1 | Tact Switches Micro SMD | [Aliexpress][aliexpress] |
| G1 | 1551G Case | 1 | 1551GFLBK | [Reichelt][reichelt] |


[reichelt]: http://www.reichelt.de
[mouser]: http://mouser.com
[aliexpress]: http://www.aliexpress.com
[digikey]: http://www.digikey.de