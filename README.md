# Mysteripad

#### WARNING: This project is a work in progress and hasn't been validated yet.

<img src="https://github.com/piit79/mysteripad/raw/main/mysteripad_pcb.png" width="300" align="left" alt="Mysteripad PCB" />

Mysteripad is a through-hole numeric keyboard (or "numpad") matching the form 
factor of the [Mysterium keyboard]((https://github.com/piit79/mysterium)) 
([original](https://github.com/coseyfannitutti/mysterium)), much like the 
[Discipad](https://github.com/piit79/discipad) 
([original](https://github.com/coseyfannitutti/discipad)) matches the 
[Discipline](https://github.com/piit79/discipline) 
([original](https://github.com/coseyfannitutti/discipline)).

Mysteripad was inspired by (but is not based on) the [Discipad](https://github.com/coseyfannitutti/discipad) by Bryan of [cftkb.com](https://cftkb.com/).

## Features

* 17-22 keys, 0-4 rotary encoders (6 rows, 4 columns)
* Hotswappable using Kailh/Gateron hotswap sockets
* All 4 top row positions support either a switch or an EC11 rotary encoder - 4 encoders can be installed at the same time¹
* Optional split 0 support (2x 1u instead of 2u)
* TRRS socket for connection to the next 42. Keebs revision of the Mysterium (V1.5e) via a 4-pin AUX (TRRS) cable (using the I²C bus) so that a single USB cable can be used for both keyboards, similar to split keyboards

¹ To reduce the number of required I/O pins from 8 to 5, any two adjacent encoders share an I/O pin. Therefore, rotating any such encoders at higher speed simultaneously might not work correctly. Other combinations (1-3, 1-4, 2-4) should not be affected.

## Kit availability

You can grab the Gerber zip files from [releases](https://github.com/piit79/mysteripad/releases) (coming soon), have the PCBs made at one of the fabs and order all the electronic components at your favourite electronics store.

A complete kit will also be available from [42. Keebs](https://42keebs.eu/) sooner or later (probably in July 2022).

## TODO

* ~~Add PCB bottom plate~~
* ~~Add PCB switch plate~~
* ~~Add acrylic cover drawing~~
* Create QMK firmware
* Add BOM
* Add build guide

## Revision history

* v1.0 (26/06/2022) - Initial version