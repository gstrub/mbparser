# mbparser
**mbparser** is a simple C++ library to read data from a modbus RTU slave and validate the crc.
This implementation uses a state machine to consume token by token.
Supports all modbus function codes. 

It is typical the core a modbus client implementation, which handles all the hardware and ambient stuff. 

Was original developed to read from a Eastron SDM72D-M Smartmeter. But can be used for any other device to parse its response.

Is natural evolution of my old mbutil library (which was C-Style but C++).

## Disclaimer
Uses C11 on ESP 8266. May not run with other arduino devices (not tested).

## Usage / Example
See example directory.

## todo
* modbus exception handling?