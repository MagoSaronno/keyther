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

## Disclaimer
All the designs and files are provided "AS IS" without any warranty or support.

## Be Aware
The Keyther Keyboard is designed to be used with **straight-through cables**, not the crossover ones. If you were to accidently connect the two halves of the keyboard with the latter type you should not experience any critical short circuit. 
Notwithstanding the relative safety of the socket connections' layout, it is advisable to ***always check the cable you intend to use in advance***.

### Bill of Materials
The required components needed to assemble the keyboard are the following:
- 2x PCB boards
- 2x STM32F401CC BlackPill microcontrollers (on [AliExpress](https://it.aliexpress.com/item/1005005953179540.html?))
- Pins and sockets for the microcontrollers (blackpill needs 20 pin stripes)
- 42 Kailh Choc ***v1*** switches
- 42 Kailh Choc hot-swap sockets
- 42 compatible keycaps
- 2x RJ45 sockets (RJHSE type, e.g. the [RJHSE-XM80](https://docs.rs-online.com/b456/A700000007566767.pdf "The technical drawing of the socket"), which you can find on [AliExpress](https://it.aliexpress.com/item/1005007661898327.html?))
- 1x Ethernet cable
- 1x USB-C cable compatible with your computer

### Ordering the PCB



### How to Assemble the keyboard



### Firmware



## Feedback

