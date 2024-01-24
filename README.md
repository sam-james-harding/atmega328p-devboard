# atmega328p-devboard

This is my own custom development board, made for the ATmega328P. I created this both as learning experience (in PCB design and in soldering SMD components), and as a practical device to assist in prototyping.

![PCB Image](https://github.com/sam-james-harding/atmega328p-devboard/blob/main/documents/pcb.png)

## Features
- Micro-USB B connection providing power and allowing serial communication
- USB-to-UART functionality via the MCP2221A IC
- Regulated 3.3V supply: power, supplied either through the USB connection or the VIN pin, can be supplied at up to 6V (using the MCP1825 voltage regulator)
- Switches for both power and USB-to-serial functionality
- LEDs to show power status and serial communication
- 16MHz crystal
- Reset button
- 6-pin ISP header (i.e. for AVRISP or the Pololu AVR programmer)

## Drawings
- [Schematic](https://github.com/sam-james-harding/atmega328p-devboard/blob/main/printouts/Schematic.pdf)
- PCB [front](https://github.com/sam-james-harding/atmega328p-devboard/blob/main/printouts/PCB%20Front.pdf)
and [back](https://github.com/sam-james-harding/atmega328p-devboard/blob/main/printouts/PCB%20Back.pdf)
