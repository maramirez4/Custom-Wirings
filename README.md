# JDR94 Custom Wiring — V4.0

An open guitar electronics project developed for a Jackson JDR94 electric guitar.

## Overview

This project documents a custom passive wiring system design for electric guitar that combines:

* 2 humbuckers — bridge and neck positions
* 1 mini-humbucker pickup — middle position
* 5-way 3-pole superswitch
* 6-way dual-axis ultraswitch
* 2 push-pull potentiometers: one switch is for single-coil simulation and the other is to reverse the phase of the middle pickup
* Single-coil simulation circuit with passive filtering and pickup compensation
* Latching blower switch — engages the bridge pickup directly to the output
* Momentary killswitch — cuts the signal when pressed, useful in certain playing contexts
* Treble-bleed circuit

This switching system provides 42 different sounds across the different superswitch/ultraswitch inner workings. 

## Schematic

**[Download the complete V4.0 schematic](JDR94%20Custom%20V4.0%20%282026-10-30%29.pdf)**

The wiring system provides multiple pickup and coil configurations through the main 5-way superswitch, including:

* Bridge humbucker series
* Neck humbucker series
* Inner and outer coils in parallel
* Superstrat middle pickup configurations 
* Neck/bridge combinations (series and parallel)
* Bridge humbucker parallel
* Neck humbucker parallel
* Single-coil simulation for both humbuckers and the mini-humbucker

The dual-axis ultraswitch provides the following configuration banks when used in tandem with the main superswitch:

| Position | Function                              |
| -------- | ------------------------------------- |
|  1       | Inner/Outer coils & both humbuckers   |
|  2       | Superstrat mode: middle in splits     |
|  3       | Parallel set: bridge, neck or both    |
|  4       | Same as 1 but with the middle pickup  |
|  5       | Mirrored splits: both humbuckers      |
|  6       | Same as 3 but with the middle pickup  |

For the complete switching logic and circuit details, see the schematic.

The schematic includes the complete wiring diagram, switching logic, component values, pickup configurations, and bill of materials.

## Version

**V4.0** is the current documented version of the design.

Designed and documented by **Marco Antonio Ramírez**.

## License

This hardware design is released under the **CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P-2.0)**.

You are free to use, study, modify, build, and distribute designs and products based on this work, subject to the terms of the license.

See the `LICENSE` file for the complete license text.

## Disclaimer

This project is provided as-is for educational, experimental, and personal use. Build and modify the circuit at your own risk.
