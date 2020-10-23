# μESP32
Hi! Welcome to my μESP32 project!
The purpose of this project is to make the smallest ESP32 development (dev) board that still has all the GPIO pins broken out for a user to play with!
## Goals
This project isn't seeking to solve a pressing issue, but it seeks to solve an issue none the less. These are features needed to solve the issue of the ESP32 Dev boards being very large and hard to use with a single breadboard.
* The μESP32 must be small, around the size of an Arduino Nano
* The μESP32 must have a built in USB to UART converter so it can be programmed without any additional hardware
* The μESP32 must be able to be powered over USB
* The μESP32 must have a reset button as it is sooo convienent
* The μESP32 must have a working on-board wifi antenna
* The μESP32 must be robust - It won't be easy to break and it will be a quality product
* The μESP32 must have status LEDs built in for users to play with
## Current Features
The μESP32 is based on the ESP32-Pico-D4 chip from Espressif. This powerful microcontroller comes packed with processing power, peripherals, and storage. The μESP32 development board has all the necessary hardware to program and run the ESP32-Pico-D4 built-in. The list of features on the μESP32 Dev board:
* ESP32-Pico-D4 processor
* Wifi or Bluetooth antenna
* CP2102 USB to UART converter with dual transistors for programming
* 4MB PSRAM
* USBC connector
* Two 600mA 3.3V low-dropout voltage regulators
* 2A fuse for the USB power line
* Diode for reverse voltage protection on the USB power line
* Reset and IO0 buttons
* 3.7V LiPo battery charge circuitry
* 3.7V LiPo battery protection
* Voltage divider connected to IO4 to monitor battery voltage
* RGB LED connected to pins IO12 (Red), IO13 (Green), and IO14 (Blue)
* RX and TX LEDs
* LED connected to IO2
* Power LED
## Where I Am At So Far
Currently, I am on revision 0.6 of my μESP32. There have been 6 major iterations or redesigns since I have begun this project. Once I feel this project is ready to be released to the world, the current revision will become revision 1.0 and I will attempt to produce my design.
