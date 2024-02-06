# RF-CONNECTOR v1.0.0 hardware 

| View | Top | Bottom |
| ---- | --- | ------ |
| <img src="doc/t-view.png" alt="drawing" width="300"> | <img src="doc/t-view-top.png" alt="drawing" width="300"/> | <img src="doc/t-view-bottom.png" alt="drawing" width="300"/> |
|  | <img src="doc/r-view-top.jpg" alt="drawing" width="300"/> | <img src="doc/r-view-bottom.jpg" alt="drawing" width="300"/> |

## Features

## Wiring

Schematic features. Schematic can be provided via issue.

**Connectors**

The node has connectors which are described in the table below.

| N | Connector | Description |
| - | - | - |
| 1 | A1, A2 |  |
| 2 | B1, B2 |  |

[Here](https://docs.raccoonlab.co/guide/wires/) you can find manufacturer part number of connectors it self and its mates.

## Pin configuration and functions

| Pin N | A1 | Pin N | A2 | Pin N | B1 | Pin N | B2 |
| ----- | ---------------- | ----- | ---------------- | ----- | ---------------- | ----- | ---------------- |
| 1 | NetA1_1 | 1 | NetA2_1 | 1 | NetA1_1 | 1 | NetA2_1 |
| G1 | NetA1_G1 | G1 | NetA2_G1 | S1 | NetA1_G1 | S1 | NetA2_G1 |
| G2 | NetA1_G1 | G2 | NetA2_G1 | S2 | NetA1_G1 | S2 | NetA2_G1 |
| S3 | NetA1_G1 | S3 | NetA2_G1 |
| S4 | NetA1_G1 | S4 | NetA2_G1 |


Here you can see all connections of MCU.

<img src="doc/pinout.png" alt="pinout"/>

| MCU PIN         | PIN Numer | NET Name | Description |
| ---------- |  -- | --------------  | - |


## Specifications

**Mechanical**

Scheme is shown on the picture below. CAN model can be provided via email request or issue on github or downloaded on GrabCAD (opens new window).

<img src="doc/drw.png" alt="drawing" height="400"/>

|       | Width, mm | Length, mm | Height, mm |
| ----- | --------- | ---------- | ---------- |
|Outline|      44.0 |       29.2 |        9.2 |
|PCB    |      44.0 |       16.5 |        1.6 |

Total weight of device less than 50 g.

### Housing

Information about case presented here.

### Absolute Maximum Ratings

### Recommended operating conditions

### ESD ratings

### MTFF

## Integration

**Recommended mechanical mounting**

**Connection example diagram**

### Power Supply Recommendations

Device is designed to operate from an input voltage supply range between 4.5 V and 5.5 V over CAN2 or CAN3 connector, or 5.5 - 30 V from CAN1. This input supply must be able to withstand the maximum input current and maintain a stable voltage. The resistance of the input supply rail should be low enough that an input current transient does not cause a high enough drop that can cause a false UVLO fault triggering and system reset. The amount of bulk capacitance is not critical, but a 47-uF or 100-uF electrolytic capacitor is a typical choice.

## Revision history

|View |Version| Date| Description|
|-    |-      |-    |-           |



## Order details

### PCB Specification Selection

- Board type : Panel by PCBWay
- Break-away rail: Yes
- Instructions:
~~~
Final size is larger ( 44.0 x 29.2 mm ) than board it self ( 44.0 x 16.5 mm), 
take a look at the picure in attachements. 
Panel should be designed to be able to install PWM1, PWM2 while assembly.
~~~
- Route Process: Panel as PCBWay prefer
- X-out Allowance in Panel:  Accept

- Size (single): 44.0 x 16.5 mm
- Quantity (single): 200
- Layers: 2 -   ['L1', 'L4'] check [PCBway layer stack](https://www.pcbway.com/multi-layer-laminated-structure.html)

- Material: FR-4
- FR4-TG: TG 150-160
- Thickness: 1.6
- Min Track/Spacing: 28/28mil (0.7 mm)
- Min Hole Size: 0.3 mm
- Solder Mask: Black
- Silkscreen: White
- Edge connector: No
- Surface Finish: HASL with lead
- Yes - Tick means you accept we might change "HASL" to "ENIG" at our discretion without extra charge.
- Via Process: Tenting vias
- Finished Copper: 1 oz Cu
- Other Special request:
~~~
Final size is larger ( 44.0 x 29.2 mm ) than board it self ( 44.0 x 16.5 mm )
~~~

### Assembly Service

- Turnkey
- Board type : Panelized PCBs
-  Assembly Side(s): Both sides
- Quantity: 200
- Contains Sensitive components/parts - No; 
- Do you accept alternatives/substitutes made in China? - Yes

- Number of Unique Parts: 0
- Number of SMD Parts: 0
- Number of BGA/QFP Parts: 0
- Number of Through-Hole Parts: 0

### Additional Options

- Firmware loading: Yes
- Detailed information of assembly:
~~~
Firmware is in attachements.
Take a look at the picure in attachements should be installed from the side.
~~~

## Device and Documentation Support

- [User manual]()
- [Hardware docs](doc/doc.pdf)

## Device Support

- [Firmware sources]()
- [Firmware binary]()

## TERMS OF USAGE / LICENCE

The material provided in this Github repository is subject to the following conditions. 

Firmware files: All firmwares are free (but not open source). Besides unlimited private use you are also granted the permission to use them for commercial purposes under the condition that (1) you dont modify the firmware, e.g. remove or change copyright statements, (2) provide it for free, i.e. dont charge any explicit or implicit fees to your customers, and (3) correctly and clearly cite the origin of the firmware and the project web page in any product documentation or web page. 

Hardware files: All hardware, for which material is provided, is open source hardware, under the terms of the TAPR Open Hardware License as published by the Free Hardware Foundation, see http://www.tapr.org/ohl.html. The TAPR license explicitly permits essentially unlimited commercial use, with only few conditions such as that copyright logos are not removed.

