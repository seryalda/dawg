## Top
# 🎉 4-Channel AC Relay Driver Board for Arduino and ESP Microcontrollers v1.0.0
### ◀️ [Back](/)
<img src="images/3dv1.png" alt="PCB Back" width="300">

<!--📷-->

## Table of Contents

- 📚 [Overview](#overview)
- 🎯 [Features](#features)
- 🛠️ [Things you need to know](#things-you-need-to-know)
- ⚙️ [Installation](#installation)
- 🖥️ [Compatible Processor Boards](#compatible-processor-boards)
- 🤝 [FAQ](#faq)
- 🤝 [Disclaimer](#disclaimer)
- 📝 [License](#license)


## Overview

The DAWG AC Relay Driver Board is a purpose-built, specialized solution for electronics projects. Measuring 76mm x 86mm, this RAIL DIN board with two screw holes (25mm center to center apart) offers a reliable means to control AC CONTACTORS or Industrial DC Relay Switches with DC voltage exceeding 12VDC. Unlike standard relays, this 4-channel relay driver serves as an intermediary, allowing low-voltage output controllers like Arduino and ESP microcontrollers to effectively activate external DC relay switches using user-selected AC voltages.

Powered by an external 5VDC source, the board simplifies the control of multiple relay switches for diverse applications, making it an ideal choice for various electronic projects.

### Features
- 4-channel relay driver board for AC CONTACTORS and Industrial DC Relay Switches.
- Designed to work with low-voltage output controllers like Arduino and ESP microcontrollers.
- Enables control of external DC relay switches using user-selected AC voltages.
- Dimensions: 76mm x 86mm RAIL DIN board with two screw holes.
- External 5VDC power source for operation.
- Ideal for applications requiring reliable and efficient relay driving.

[🔝 Top](#top)

## Things you need to know

NA

[🔝 Top](#top)

## Installation

Things and diagram you will need, for wiring and to implement RAIL DIN configurations:

| How to Wire Diagram | Sample Wiring | Slotted Metal Rail DIN  | Screws M3 D=3mm, L=6mm   | Mounting Brackets (25mm center to center) |
|--------------------|--------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
| <img src="images/ex1.png" alt="PCB Back" width="150"> | <img src="images/wiring2.png" alt="PCB Back" width="150"> | <img src="images/slotted-metal-rail-din1.jpg" alt="PCB Back" width="150"> | <img src="images/m3-screws1.jpg" alt="PCB Back" width="150"> | <img src="images/rail-din-mounting-bracket1.png" alt="PCB Back" width="150"> |
|||[🛍️ BUYHERE](#)|[🛍️ BUYHERE](#)|[🛍️ BUYHERE](#)|

  
[🔝 Top](#top)

## Compatible Processor Boards

DAWG Board v1.0.0 also works with below Processor Board:

| Board              | Link                                       | Image                                                                                                 | Description                                                                                                                                      | GPIO Output Pins     |
|--------------------|--------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
| **Foghorn v1.0.0** | [FOGHORN](https://github.com/seryalda/foghorn) | ![PCB Back](https://github.com/seryalda/foghorn/raw/main/1.0.0/3dv1.png) | The board integrates with the Foghorn Version 1.0.0 Processor Board. It's an ESP8266 NodeMCU v3 compatible board with a screw terminal block output mapped to GPIO pins 4, 5, 12, and 14, allowing control of up to 4 external switch relays or CONTACTORS. | 4, 5, 12, 14 |



Explore the compatibility of DAWG with these processor boards to enhance your projects.

[🔝 Top](#top)

## FAQ

N/A

[🔝 Top](#top)

## Disclaimer

NA

[🔝 Top](#top)

## License

NA

[🔝 Top](#top)

<!--

i am creating an amazon listing for below special purpose printed circuit board, this board primary purpose is to 
act as a mounting board for ESP8266 nodeMCU V3,  

create an amazon listing descriptions in HTML format with complete cool emoji, should be easy to read and use simple terms 

and create also a bulleted features

extract this from below summary

the format is 

TITLE
DESCRIPTIONS 
FEATURES


FOGHORN BOARD
MOUNTING dual 15 pins female headers FOR ESP8266 NODEMCU V3
15 pins male and female mapped to ESP module pins for ease of use using jumper wires connections to projects
analog pin header for A0 
5 pins terminal screw block mapped directly to ground, gpio 4,5,12 and 14 microcontroller
dc supply options choose between 5vdc directly to VIN or 12vdc power source and use built in 
dc regulator to convert 12vdc to produce 5vdc and send to VIN, to use this option you need to short the XX jumper pins of JP1
there are also two pin male/female headers for allowing user to connect using jumper wires, 

the board layout  76 mm width by 86 mm high is designed to be RAIL DIN compatible, with screw hole on the sides of 25mm center to center spacing 

DHT header ready, you can insert DHT11 or DHT22 in the 5 pins female headers, 

all headers pins are 1.24mm standard spacing

-->
