# iot-microwave

## Overview

This is the default Mongoose OS app + modified init.js.
It's for controlling a microwave via MQTT. 

For the microwave, you can hack one with photo relays or regular relays.
Basically what you need to do is to simulate the depression of button pushes.

Make sure you unplug your microwave before desassembly.

First, take the top cover and the front panel off.

Second, find ribbon cables that connect buttons and the main board.

Third, solder jumber cables to the board so that you have another set of "ribbon cables".

Forth, short every combinations of the jumber cables and find whith combination does min button push, 10 sec button push, start button push, etc.

Third, connect jumber cables and ESP32 via photo relays.


## How to install this app

- Install and start [mos tool](https://mongoose-os.com/software.html)
- Switch to the Project page, find and import this app, build and flash it:

<p align="center">
  <img src="https://mongoose-os.com/images/app1.gif" width="75%">
</p>
