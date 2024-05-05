# OLED Stats Display for Raspberry Pi

This Python script runs in the background of a Raspberry Pi and displays basic stats on an OLED screen. It has been modified to support the SH1106 chip and other compatible chips instead of the SSD1306. 

## Original Author

This project is based on the work of [Michael Klements](https://github.com/mklements/OLED_Stats), whose build guide can be found [here](https://www.the-diy-life.com/add-an-oled-stats-display-to-raspberry-pi-os-bullseye/).

## Features

- Displays basic system statistics such as CPU temperature, IP, memory usage, disk space, etc. on an OLED screen.
- Supports the SH1106 chip and other compatible chips.
- Runs in the background of the Raspberry Pi.

## Dependencies

- [Luma.OLED](https://github.com/rm-hull/luma.oled) library

## Installation

Use the instruction on [Michael Klements](https://github.com/mklements/OLED_Stats) build guide.
You don't have to install the adafruit library. Install the luma.oled library instead.
Use this script instead of the script mentionend in the build-guide.




