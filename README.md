# Voltage Measurement System with LED Display

## Overview
This project presents a comprehensive solution for measuring and displaying AC voltage levels accurately. Utilizing the ICL7107 analog-to-digital converter (ADC) with a precision of 3½ digits, the system offers high-precision voltage readings in a digital format, directly interfacing with LED displays for easy readability. Designed for minimal power consumption, it is particularly suited for battery-operated devices.

## Key Features
- **High Precision Measurement:** Leverages the ICL7107 ADC for accurate voltage reading.
- **Efficient Display:** Features four 7-segment SA08-11YWA LED displays for clear output visibility.
- **Energy Efficient:** Optimized for low power consumption, ideal for battery-operated implementations.
- **Flexible Connectivity:** Utilizes FFC (Flat Flexible Cable) connectors for seamless integration and ease of maintenance.
- **Robust PCB Design:** A dual-layer PCB design with a focus on electromagnetic stability and efficiency. Features copper pours for GND on the back layer to enhance device reliability.

## Hardware Components
- **ICL7107 ADC:** The core component for analog-to-digital conversion, offering direct connectivity to LED displays.
- **AD737:** Outputs RMS value of the measured AC voltage, interfaced with the ICL7107.
- **SA08-11YWA LED Displays:** Four 7-segment displays with common anode configuration, powered by 5V.
- **FFC Connectors:** Provides a flexible and secure connection between the LED displays and the main PCB.
- **PCB Materials:** Utilizes FR4 for the dielectric layer and ENIG (Electroless Nickel Immersion Gold) for the copper surface finish for enhanced durability and solderability.

![Schematic Diagram](Full schematic.png "Full schematic (Better quality version in PDF)")
