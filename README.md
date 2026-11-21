# ESP32 WROOM Learn

A four-layer PCB design project created with KiCad 10 for learning practical schematic capture, component placement, routing, and PCB manufacturing workflows around the ESP32-WROOM-32E module.

## Main Components

- ESP32-WROOM-32E Wi-Fi and Bluetooth module
- USB-C connector with TPD2EUSB30A ESD protection
- CH340C USB-to-UART interface with automatic programming circuitry
- TLV75733 3.3 V linear regulator
- MPU-6050 six-axis motion sensor
- BME280 environmental sensor
- Test points for power rails, UART, enable, and boot signals

## PCB Layer Stack

1. `F.Cu`: components and primary signal routing
2. `In1.Cu`: continuous ground reference plane
3. `In2.Cu`: power distribution and selected low-speed signals
4. `B.Cu`: secondary signal routing and ground copper

## Project Status

Work in progress. The board is currently in the component-placement and four-layer PCB layout learning phase.

## Requirements

- KiCad 10

## Repository Contents

- `ESP32_Wroom_Learn.kicad_sch`: main schematic
- `ESP32_Wroom_Learn.kicad_pcb`: PCB layout
- `ESP32_Wroom_Learn.kicad_pro`: KiCad project settings
- `libraries/`: project-specific symbol libraries

## License

No license has been selected yet. Unless a license is added, the design remains publicly viewable but is not automatically licensed for reuse or redistribution.
