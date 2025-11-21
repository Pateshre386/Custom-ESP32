# Custom ESP32-S3 Development Board
**Status:** Prototype V1.0 | **EDA Tool:** Altium Designer

## Project Overview
A custom 4-layer development board based on the ESP32-S3 Mini. Designed to enable rapid prototyping of IoT applications with native USB-C debugging and high-efficiency power regulation.
![Board 3D View](3D_View.png)

## Key Features
* **MCU:** ESP32-S3 Mini (Dual-core XTensa LX7, 240 MHz)
* **Power:** 5V USB-C input with 3.3V/800mA LDO regulation.
* **Connectivity:** Native USB-C JTAG/Serial debugging + UART Bridge.
* **PCB Stackup:** 4-Layer (Sig / Gnd / Pwr / Sig) for 90Ω differential impedance control.

## Design View
Output Files available in the [[Hardware](/Hardware)](https://github.com/Pateshre386/Custom-ESP32/tree/649531a46ac5a9a8d4f57140923d07539d8475ee/Project%20Outputs%20for%20ESP32%20With%20USB%20C) folder.
![Schematic Preview](Final/2D_View.pdf)

## Fabrication
* Manufactured by JLCPCB.
* Design Rules: 6mil trace / 6mil space.
* Via Sizes: 0.3mm hole / 0.6mm pad.
