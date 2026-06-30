# A320-Macropad
A320 Style Speed/Heading Selector built with 2 rotary encoders, 2 pushbuttons, a status LED, and an OLED screen.firmware

# Features:
- 1x 0.9in OLED Display
- 2x EC11 Rotary encoder (One to control Speed, one to control HDG)
- 1x SK6812 Mini-e LEDs. It is a status light for the LOC button

# CAD Model:
Everything fits together using 5 M3 Bolts and heatset inserts. 4 for the case, one for the PCB. Also, it has a 5 degree tilt

It has 3 separate printed pieces. The angle, the base where the PCB sits, and the top cover. it also has 2 acrylic plates. One to cover the electronics, the other to hold the switches

Schematic

Made in Fusion360. Nifty

PCB
Here's my PCB! It was made in KiCad. The silkscreen was imported from a Figma image.

Schematic Schematic

PCB Schematic

I used MX_V2 for the keyswitch footprints. I think in retrospect, I should've added a ground plane

Firmware Overview
This hackpad uses QMK firmware for everything.

the rotary encoder changes volume. press to mute
The 4 keys currently act as macros I dynamically change in VIA.
The OLED is a cat!! Bongocat!! :3
Bongo Cat

I might add more in the future! That's it for now

BOM:
Here should be everything you need to make this hackpad

4x Cherry MX Switches
4x DSA Keycaps
5x M3x5x4 Heatset inserts
3x M3x16mm SHCS Bolts
2X M3x12mm SHCS Bolts
5x 1N4148 DO-35 Diodes.
2x WS2812B LEDs
1x 0.91" 128x32 OLED Display
1x EC11 Rotary Encoder
1x XIAO RP2040
1x Case (3 printed parts, 2 laser cut parts)
Extra stuff
Honestly I'm not quite too sure what to add here. Favourite meme? a joke?? Uhhh you can imagine it

Oh fun fact: I built mine in SF the day before github universe LOL
