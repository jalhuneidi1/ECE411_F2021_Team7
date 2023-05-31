# ECE411 Sunrise Alarm Clock - Team 7

> "Never wake-up in darkness..."

View the [Product Design Specification](./Product%20Design%20Specification%20v1.pdf) for more information.

Look at the [Project Board](https://github.com/31415pi/ECE_411_Winter_2021_Team_7/projects/1).

Schematic located at [Hardware/Schematic](./Hardware/Schematic.pdf).

![L1 Decomposition](/CAD/L1%20Decomposition.png)


## Parts List

Parts list on [google drive](https://docs.google.com/spreadsheets/d/1yFu2dnekZCLbKxV9tUKsMTaaS4XpjHtpUTBXEi358RU/edit#gid=0). [Convert to Markdown](https://tabletomarkdown.com/convert-spreadsheet-to-markdown/).

| Part (datasheet link)                                                                                                                                  | Name                                                 | Type            | Notes                        | Datasheet                                                                                                                                                                                                                                                                                                  | Website                                                                                                    | Source                                                          | Price  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------- | --------------- | ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- | ------ |
| [HT16K33](https://github.com/31415pi/ECE_411_Winter_2021_Team_7/blob/main/Datasheets/HT16K33v120(LEDcontroller).pdf)                                   | RAM Mapping 16\*8 LED Controller Driver with keyscan | LED Controller  |                              |                                                                                                                                                                                                                                                                                                            | [https://www.holtek.com/productdetail/-/vg/16K33](https://www.holtek.com/productdetail/-/vg/16K33)         |                                                                 |        |
| [PIC18F26K42](https://github.com/31415pi/ECE_411_Winter_2021_Team_7/blob/main/Datasheets/PIC18(L)F26-27-45-46-47-55-56-57K42-Data-Sheet-40001919G.pdf) |                                                      | Microcontroller | Actual Model Read from Chip. | [https://www.microchip.com/content/dam/mchp/documents/MCU08/ProductDocuments/DataSheets/PIC18(L)F26-27-45-46-47-55-56-57K42-Data-Sheet-40001919G.pdf](https://www.microchip.com/content/dam/mchp/documents/MCU08/ProductDocuments/DataSheets/PIC18(L)F26-27-45-46-47-55-56-57K42-Data-Sheet-40001919G.pdf) | [https://www.microchip.com/en-us/product/PIC18F26K42](https://www.microchip.com/en-us/product/PIC18F26K42) | EPL                                                             | $ 1.50 |
| [IRM-05-5](https://github.com/31415pi/ECE_411_Winter_2021_Team_7/blob/main/Datasheets/IRM-05(ac-5vsupply).pdf)                                         |                                                      | DC Power Supply |                              |                                                                                                                                                                                                                                                                                                            |                                                                                                            | [Mouser](https://www.mouser.com/ProductDetail/709-IRM05-5)      | $ 8.81 |
| [MOC3052TVM](https://github.com/31415pi/ECE_411_Winter_2021_Team_7/blob/main/Datasheets/MOC3052M(ACcont).pdf)                                          |                                                      | AC Controller   |                              |                                                                                                                                                                                                                                                                                                            |                                                                                                            | [Mouser](https://www.mouser.com/ProductDetail/512-MOC3052SR2M)  | $ 1.15 |
| [ACST410-8BTR](https://github.com/31415pi/ECE_411_Winter_2021_Team_7/blob/main/Datasheets/ACST410(ACswitch).pdf)                                       |                                                      | AC Switch       |                              |                                                                                                                                                                                                                                                                                                            |                                                                                                            | [Mouser](https://www.mouser.com/ProductDetail/511-ACST410-8BTR) | $ 0.85 |
| [SFH628A](https://github.com/31415pi/ECE_411_Winter_2021_Team_7/blob/main/Datasheets/SFH628A(ACsensor).pdf)                                            |                                                      | AC Sensor       |                              |                                                                                                                                                                                                                                                                                                            |                                                                                                            | [Mouser](https://www.mouser.com/ProductDetail/782-SFH6286-4T)   | $ 1.27 |
| [COM-10931](https://github.com/31415pi/ECE_411_Winter_2021_Team_7/blob/main/Datasheets/COM-10931_ATA3492BW(7seg4digitSparkfun).pdf)                    | 7-Segment Display - 4-Digit (White)                  | Time Display    |                              | [http://cdn.sparkfun.com/datasheets/Components/LED/ATA3492BW\_2.pdf](http://cdn.sparkfun.com/datasheets/Components/LED/ATA3492BW_2.pdf)                                                                                                                                                                    | [https://www.sparkfun.com/products/10931](https://www.sparkfun.com/products/10931)                         | [Mouser](https://www.mouser.com/ProductDetail/474-COM-10931)    | $ 2.63 |




Alternate [Sparkfun Time Display](https://www.sparkfun.com/products/10931).

## Tools

- KiCad. [Third Party Libraries](https://www.kicad.org/libraries/third_party/)
- [Library Loader](https://componentsearchengine.com/tools) for loading schematics into KiCad and others. [Setup Instructions](https://www.samacsys.com/kicad/)
