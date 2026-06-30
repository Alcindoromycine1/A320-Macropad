# A320-Macropad
A320 Style Speed/Heading Selector built with 2 rotary encoders, 2 pushbuttons, a status LED, and an OLED screen.firmware

# Features:
- 1x 0.9in OLED Display
- 2x EC11 Rotary encoder (One to control Speed, one to control HDG)
- 1x SK6812 Mini-e LEDs. It is a status light for the LOC button

# CAD Model:
This project was designed in Fusion 360 and is held together using M3 Screws and Heatset inserts.

<img src=assets/cad.png alt="Schematic" width="500"/><img src=assets/cad_nolid.png alt="Schematic" width="500"/>

It has 4 separate printed pieces. The base where the PCB is held, the lid, and two knobs to rotate the rotary encoders.
The knobs were used from Liam Egger's [project](https://www.printables.com/model/601969-autopilot-panel-fly-by-wire-a320neo/files) on printables.com

<img src=assets/knobs.png alt="Schematic" width="500"/>

# PCB
Here's the PCB for this project. It was made in KiCad.

Schematic

<img src=assets/schematic.png alt="Schematic" width="500"/>

PCB

<img src=assets/pcb.png alt="Schematic" width="500"/>

I used the footprints and schematic parts from Hack Club's wesbite. The OLED screen could have been better modelled, but that is a problem for the future.

Firmware Overview
This hackpad, being a interface for a flight simulator, will use MobiFlight to interact with the simulator.

BOM:

- 2x Cherry MX Switches
- 2x DSA Keycaps
- 4x M3x5x4 Heatset inserts
- 4x M3x16mm  Bolts
- 1x SK6812 MINI-E LEDs
- 1x 0.91" 128x32 OLED Display
- 2x EC11 Rotary Encoder
- 1x XIAO RP2040
- 1x Case (4 printed parts)

