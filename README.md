# JDR94 Custom Wiring — V4.1

An open guitar electronics project developed for a Jackson JDR94 electric guitar.

## Overview

This project documents a custom electric guitar wiring system design that combines:

* 2 humbuckers — bridge and neck positions
* 1 mini-humbucker pickup — middle position
* 5-way 6-pole superswitch
* 6-way dual-axis ultraswitch
* 2 push-pull potentiometers: one switch is for single-coil simulation and the other is to reverse the phase of the middle pickup while connecting it to the output
* Single-coil simulation circuit with passive filtering and pickup compensation
* Latching blower switch — engages the bridge pickup directly to the output
* Momentary killswitch — cuts the signal when pressed, useful in certain playing contexts
* Treble-bleed circuit

This switching system provides **48** different pickup configurations across all superswitch/ultraswitch inner workings. 

## Schematic

**V4.1** is the current documented version of the design.

**[Download the complete V4.1 schematic](JDR94%20Custom%20V4.1%20%282026-11-10%29.pdf)**

The wiring system provides multiple pickup and coil configurations through the main 5-way superswitch, including:

* Bridge humbucker series
* Neck humbucker series
* Inner and outer coils in parallel and series
* Superstrat middle pickup configurations 
* Neck/bridge combinations (series and parallel)
* Bridge humbucker connected in parallel
* Neck humbucker connected in parallel
* Single-coil simulation for both humbuckers and the mini-humbucker

The dual-axis ultraswitch provides the following configuration banks when used in tandem with the main superswitch:

| Position | Function                                                |
| -------- | ------------------------------------------------------- |
|  1       | Inner/outer coils in parallel and inner coils in series |
|  2       | Superstrat mode: middle in split positions 2, 3 and 4   |
|  3       | Parallel for each humbucker and outer coils in series   |
|  4       | Same as 1 but with the middle pickup added in parallel  |
|  5       | Mirrored splits: both humbuckers in positions 1 and 5   |
|  6       | Same as 3 but with the middle pickup added in parallel  |

For the complete switching logic and circuit details, see the schematic.

The schematic includes the complete wiring diagram, switching logic, component values, pickup configurations, and bill of materials.


# AM7 Custom Wiring — V3.0

Another open guitar electronics project, developed for my custom 7-string guitar equipped with two humbuckers.

## Overview

This project documents a custom electric guitar wiring system design that combines:

* 2 humbuckers — bridge and neck positions
* 5-way 6-pole superswitch
* 6-way dual-axis ultraswitch
* 2 push-pull potentiometers: one switch is for single-coil simulation and the other is to reverse the neck pickup's phase and north/south structure.
* Single-coil simulation circuit with passive filtering and pickup compensation
* Latching blower switch — engages the bridge pickup directly to the output
* Momentary killswitch — cuts the signal when pressed, useful in certain playing contexts
* Treble-bleed circuit

This switching system provides **34** different pickup configurations across all superswitch/ultraswitch inner workings. 

## Schematic

**V3.0** is the current documented version of the design.

**[Download the complete V3.0 schematic](AM7%20V3.0%20%282026-11-23%29.pdf)**

The wiring system provides multiple pickup and coil configurations through the main 5-way superswitch, including:

* Bridge humbucker series
* Neck humbucker series
* Inner and outer coils in parallel and series
* Neck/bridge combinations (series and parallel)
* Bridge humbucker connected in parallel
* Neck humbucker connected in parallel
* Single-coil simulation for each humbucker

The dual-axis ultraswitch provides the following configuration banks when used in tandem with the main superswitch:

| Position | Function                                                |
| -------- | ------------------------------------------------------- |
|  1       | Inner/outer coils in parallel and inner coils in series |
|  2       | Inner/outer coils in parallel and outer coils in series |
|  3       | Parallel for each humbucker and outer coils in series   |
|  4       | Same as 2 but with both humbuckers in positions 1 and 5 |
|  5       | Same as 5 with mixed series/parallel for both pickups   |
|  6       | Same as 3 except that the splits are all in parallel    |

For the complete switching logic and circuit details, see the schematic.

The schematic includes the complete wiring diagram, switching logic, component values, pickup configurations, and bill of materials.


# License

This hardware design is released under the **CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P-2.0)**.

You are free to use, study, modify, build, and distribute designs and products based on this work, subject to the terms of the license.

See the `LICENSE` file for the complete license text.

## Disclaimer

This project is provided as-is for educational, experimental, and personal use. Build and modify the circuit at your own risk.
Designed and documented by **Marco Antonio Ramírez**.
