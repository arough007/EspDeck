# EspDeck

This is a StreamDeck inspired macro pad powered by EspHome for use with Home Assistant. Each key has 3 different actions it can perform, single click, double click, and click + hold. These can all be tied to different automations in Home Assistant. This project is made for ESPHome (hardware + ESPHome Configuration).

[![Made for ESPHome](/assets/images/made-for-esphome-black-on-white.svg)](https://esphome.io/guides/made_for_esphome.html)


# Functionality
ESPDeck provides a macropad type input set to Home Assistant based on ESPHome. This includes 3 modes of input for each keyswitch. 

  * Single Click
  * Double Click
  * Click and Hold

# Hardware Used
  * 1 x ESP8266 / NodeMCU
  * 9 x Relegendable KeyCaps (waterslide decal paper can also be used with existing keycaps, especially blank ones)
  * 9 x Mechanical key switches
  * 3d printer material
  * PCB (manufactured via JLCPCB)

# Construction

 - Solder the vertical key row first.
 - After that solder the ESP to the other site.
 - You can then solder the rest of the keys.
   - You maybe have to clip the pins of the ESP to fit the keycaps or remove some of the plastic on the bottom of the keys if the solder joints are too big.

# Case

Case completely designed from scratch.
The top part should be printed with the grid on top and supports enabled. This way the surface finish is better.
The bottom part should also have supports enabled to print the overhangs on the clips correctly.


# Configuration

keypad.yaml


# Contributing
Contributions are welcome to the project
