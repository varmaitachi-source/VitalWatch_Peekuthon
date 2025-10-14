# This directory provides the Hardware overview for the devices 

            Vital Watch (Wearable)


Hardware Overview

ESP32 – Core controller for data processing and communication

Vital Sensors – Heart rate, SpO₂, and temperature sensing

MAX485 – RS485 communication interface

Display Module – Real-time patient data visualization

Ethernet + Wi-Fi – Hybrid online/offline connectivity

TP4056 – Li-ion battery charging module

DW01 + FS8205A – Battery protection circuit

AMS1117 – 3.3V voltage regulation



               Vital Hub

Receives encrypted data from multiple Vital Watches.

Uses ESP32 for local and Ethernet-based data handling.

Includes MAX485 module for RS485 communication.

Integrates a Display module for quick ward-level visualization.

Features Ethernet and Wi-Fi for hybrid online-offline operation.



                    Power Distribution

Battery → TP4056 → DW01 + FS8205A → PCU → AMS1117 → ESP + peripherals.

Power monitored and distributed to Display, Ethernet, and RS485 modules.

Polyfuse and TVS diode protection for surge control and safety.
