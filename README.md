# stm32-with-onboard-spi-sensor
# STM32F103C8T6 and TC-72 Temperature Sensor Integration

This repository documents the integration of the STM32F103C8T6 microcontroller with the TC-72 temperature sensor. The project includes the design of a custom PCB with a focus on power management, USB connectivity, crystal oscillator circuits, and other necessary microcontroller peripherals.

## Features
- **Microcontroller**: STM32F103C8T6
- **Temperature Sensor**: TC-72
- **Custom PCB Design**: Includes power section, USB connectivity, crystal oscillator, and other supporting circuits.

## Project Highlights
1. **Sensor Integration**: 
   - Interfaced the TC-72 temperature sensor with STM32F103C8T6.
   - Configured SPI communication for temperature data retrieval.

2. **PCB Design**:
   - Designed a custom 4-layer PCB layout.
   - Integrated power management circuits.
   - Added USB interface for communication and power.
   - Included an external crystal oscillator circuit for accurate clock generation.

## Getting Started
### Hardware Requirements
- STM32F103C8T6 microcontroller
- TC-72 temperature sensor
- Custom PCB (designed for this project)
- USB cable for power and communication

### Software Requirements
- STM32CubeIDE (or equivalent IDE for STM32 development)
- PCB design files (compatible with [insert PCB tool, e.g., KiCAD, Altium])

### Steps to Run
1. Flash the firmware onto the STM32F103C8T6 microcontroller using a USB connection or ST-Link programmer.
2. Power the circuit through USB or an external power source.
3. Monitor temperature data via [describe output method, e.g., UART, USB, etc.].

## Future Work
- Enhance firmware for additional sensors.
- Optimize PCB design for reduced size.
- Add support for low-power modes.
