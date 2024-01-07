# atmega328p-devboard

This is my own custom development board, made for the ATmega328P. This serves as both a learning experience and a practical device to assist in prototyping.

## Features
- Micro-USB B connection: the board can be powered through this connection, and, using the MCP2221A IC, serial communication can be conducted between the host computer and the ATmega328P
- Regulated 3.3V supply: power, supplied either through the USB connection or the VIN pin, can be supplied at up to 6V (using the MCP1825 voltage regulator)
- 16MHz crystal
- Switches for both power and USB-to-serial functionality
- Reset button
- 6-pin ISP header (i.e. for AVRISP or the Pololu AVR programmer)
