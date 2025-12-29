# Keyther Keyboard
The Keyther Keyboard represents an attempt at perfecting the already great [Cantor Classic](https://github.com/diepala/cantor "The original project"). The name comes from the combination of the substantives **Keyboard** and **Ethernet**, due to the use of an RJ45 socket. 

### What changes from Cantor

1. The often *criticised* and *feared* TRRS socket is replaced with the more secure RJ45 (Ethernet), to ultimately avoid potential *critical* integrity issues caused by accidental disconnection or hot-plugging.

2. The design introduces **hot-swappable** Kailh Choc **sockets**, in a certain sense partially *contravening* to the original Cantor's purpose of being the least annoying keyboard to assemble. 
Nonetheless, once the initial assembly is finished you won't have to desolder all the 42 switches to change them, representing a good time investment for possible further changes to the keyboard components.

3. Furthermore, the design slightly *increases* switches' horizontal spacing, accommodating more easily larger hands **without** any modifications to the overall PCB size

### What does not change

The keyther keyboard keeps (*for the most part*) the original concepts that were at the origin of Cantor, that are the diodeless design and the use of an invertible PCB design, to ultimately avoid cuttable costs.

### Why RJ45 instead of USB-C or magnetic pogo pins sockets?

The main reason for the use of RJ45 sockets is the ease of solder of such components, their overall diffusion and the widespread presence of premade cables of different kinds, like coiled, straight and flat.

Additionally, the number of pins present on the socket allows possibly the addition of two optional communication lines between PCBs for whatever use.

# Be Aware
The Keyther Keyboard is designed to be used with ***STRAIGHT-THOUGH CABLES***, not the crossover ones.

***Always check the cable type before connecting the two halves***.

## Disclaimer
All the designs and files are provided "AS IS" without any warranty or support.

## Links Index

[Ordering Tutorial]()

[Assembling Tutorial]()

[Firmware Guide](https://qmk.fm/guide "The default guide for the Cantor Keyboard")

## Quick Guide

### Bill of Materials (BOM)
The required components needed to assemble the keyboard are the following:
| N. | Item                                                                                                                                        | Notes                                                                  |
|----|---------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| 2  | PCB board                                                                                                                                   |                                                                        |
| 2  | STM32F401CC BlackPill microcontrollers                                                                                                      | on [AliExpress](https://it.aliexpress.com/item/1005005953179540.html?) |
| 4  | 20 pin stripes                                                                                                                              | *usually included with the Blackpill*                                  |
| 42 | Kailh Choc ***v1*** switches                                                                                                                | namely the Kailh PG1350                                                |
| 42 | Kailh Choc hot-swap sockets                                                                                                                 |                                                                        |
| 42 | Kailh Choc ***v1*** compatible keycaps                                                                                                      |                                                                        |
| 2  | RJ45 sockets (RJHSE type, e.g. the [RJHSE-XM80](https://docs.rs-online.com/b456/A700000007566767.pdf "The technical drawing of the socket"))| on [AliExpress](https://it.aliexpress.com/item/1005007661898327.html?) |
| 1  | Straight-through Ethernet cable                                                                                                             |                                                                        |
| 1  | USB-C cable compatible with your computer                                                                                                   |                                                                        |

### Ordering the PCB
To order the PCB you will need the gerber files present in the [Release section](). Then you can either compare the prices on [PCBShopper](https://pcbshopper.com/ "A price comparison site for printed PCBs") by choosing a dimension of 150x90mm or upload them directly to the PCB manufacturer's website of choice.

You can refer to the [Ordering Tutorial]() page which provides a step-by-step guide on the ordering procedure.

> I personally prototyped my PCBs using JLCPCB, primarily due to lower prices. However, these may vary depending on your customs policies and regional shipping rates.

### Firmware
It is preferable to test if the microcontroller is not defective before assembling the keyboard.

The Keyther Keyboard uses the [QMK Firmware](https://qmk.fm/), specifically the same as the Cantor Keyboard. You can easily follow the [guide](https://qmk.fm/guide "The default guide for the Cantor Keyboard") on the QMK website to *customise* and *compile* the firmware.

To add **language specific characters** (such as *accented* or *umlaut* vowels) you can follow this [additional guide]().

To flash the firmware onto the microcotroller you will need to set it in bootloader mode first:
- Press and hold the BOOT0 button.
- Press and release the NRST button.
- Release the BOOT0 button.

Now you will be able to flash the firmware and check if the microcontroller works properly.

### Assemble the keyboard
To assemble your Keyther Keyboard you will need a soldering iron and tin of your choice. You can also follow the [Assembling Tutorial]().

## Feedback
You can fill [this form](https://forms.gle/tCP48DNiQqiqbWwy6 "Leave here your much appreciated feedback") to let me quickly know of any potential improvements or issues with the project. 
