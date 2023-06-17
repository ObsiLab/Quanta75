<img align="left" height="140" src="https://user-images.githubusercontent.com/23436953/233587902-4c61e8fd-951d-454f-9dfa-1ea4b9c6a239.svg">

# Quanta Mechanical Keyboard
Custom hot-swap 75% ISO keyboard with integrated USB hub including one vertical upward-facing USB A port for Windows Hello fingerprint readers.  

### Project advancement : [Quanta's Github Project](https://github.com/orgs/ObsiLab/projects/2)  

## Documentation
Documentation about Quanta can be found on [the Quanta website: quanta.obsilab.com](https://quanta.obsilab.com).

## PCB
Quanta exists in multiple versions:
- RP2040 Stamp microcontroller board by Solder Party
  - General components
  - JLCPCB assembly service optimized BOM
- RPi Pico microcontroller board
  - General components
  - JLCPCB assembly service optimized components
- Bare RP2040 microcontroller chip
  - General components
  - JLCPCB assembly service optimized components

All of them are using SMD components but no smaller than 0603 and on hand-solderable pads (a complete through-hole PCB could be coming next 👀). A PCB assembly service is still recommended.

#### See the PCB and schematic in [KiCanvas' Browser PCB viewer](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2FLucasPlacentino%2FQuanta%2Ftree%2Fmain%2FQuanta_RP2040Stamp_JLCPCBAoptimized).


## Firmware (_WIP_)
<img align="left" height="50" src="https://user-images.githubusercontent.com/23436953/178243491-15feeaaf-8cb2-4e8b-91a6-5bcb316d6a1f.png">

[rmk_firmware](https://github.com/ObsiLab/rmk_firmware) _WIP_  
RMK is a keyboard firmware written in Rust, inspired by QMK or KMK. Originally built for the Quanta.

QMK config for the Quanta: _WIP_  

VIA config for the Quanta: _WIP_  

VIAL config for the Quanta: _WIP_  

## Design :
See the design details [here](/design).

## License
Project licensed under [CERN-OHL-P v2](LICENSE).

> Logos are licensed under [CC BY-NC-ND 4.0 ](https://creativecommons.org/licenses/by-nc-nd/4.0/) (more info [here](/design/README.md)).
