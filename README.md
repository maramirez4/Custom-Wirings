# JDR94 Custom Wiring — V3.3

An open guitar electronics project developed for a Jackson JDR94 electric guitar.

## Overview

This project documents a custom passive wiring system design for electric guitars with two humbuckers and one single-coil pickup.

The system combines:

* 2 humbuckers — bridge and neck positions
* 1 single-coil pickup — middle position
* 5-way 4P5T superswitch
* 5-way 4P5T rotary switch
* 2 push-pull potentiometers
* Treble-bleed circuit
* Single-coil simulation circuit with passive filtering and pickup compensation
* Latching blower switch — engages the bridge pickup directly to the output
* Momentary killswitch — cuts the signal when pressed, useful in certain playing contexts

## Switching System

The wiring system provides multiple pickup and coil configurations through the main 5-way superswitch, including:

* Bridge humbucker series
* Neck humbucker series
* Neck humbucker parallel
* Inner and outer coils
* Neck/bridge combinations
* Single-coil simulation for both humbuckers

The rotary switch provides the following configurations when used in tandem with the main superswitch:

| Position | Function                              |
| -------- | ------------------------------------- |
| -2       | Bridge parallel                       |
| -1       | Middle only — superswitch is bypassed |
| 0        | Bridge series (default configuration) |
| +1       | Middle parallel to superswitch output |
| +2       | Middle parallel and out-of-phase      |

For the complete switching logic and circuit details, see the schematic.

## Schematic

**[Download the complete V3.3 schematic](./JDR94_Custom_Wiring_V3.3.pdf)**

The schematic includes the complete wiring diagram, switching logic, component values, pickup configurations, and bill of materials.

## Version

**V3.3** is the current documented version of the design.

Designed and documented by **Marco Antonio Ramírez**.

## License

This hardware design is released under the **CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P-2.0)**.

You are free to use, study, modify, build, and distribute designs and products based on this work, subject to the terms of the license.

See the `LICENSE` file for the complete license text.

## Disclaimer

This project is provided as-is for educational, experimental, and personal use. Build and modify the circuit at your own risk.
