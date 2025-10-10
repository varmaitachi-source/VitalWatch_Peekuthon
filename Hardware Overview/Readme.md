Vital Watch (Wearable):


Powered by a Li-ion battery with protection (DW01 + FS8205A MOSFETs).

Charging via TP4056 IC.

AMS1117-3.3V regulator provides stable 3.3V for ESP and sensors.

ESP8266/ESP32 microcontroller handles sensing, encryption, and transmission.

Sensors: Pulse oximeter and temperature sensor.

SOS Button: Manual emergency alert trigger.



Vital Hub:

Receives encrypted data from multiple Vital Watches.

Uses ESP32 for local and Ethernet-based data handling.

Includes MAX485 module for RS485 communication.

Integrates a Display module for quick ward-level visualization.

Features Ethernet and Wi-Fi for hybrid online-offline operation.



Power Distribution:

Battery → TP4056 → DW01 + FS8205A → PCU → AMS1117 → ESP + peripherals.

Power monitored and distributed to Display, Ethernet, and RS485 modules.

Polyfuse and TVS diode protection for surge control and safety.
