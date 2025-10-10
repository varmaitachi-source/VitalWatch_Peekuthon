This directory contains the unique architecture we have used in our Vital Environment

Our ward monitoring architecture is designed for maximum reliability. Multiple Vital Watch wearables worn by patients act as nodes that transmit encrypted health data directly to a central Vital Hub located at the nursing station. This system includes an intelligent Hybrid Switching mechanism: when the hospital’s internet (Wi-Fi/Ethernet) is available, it syncs data to the cloud in real-time. If the internet fails, the system automatically switches to a private, high-speed local network (ESP-NOW) to ensure uninterrupted monitoring.

To guarantee signal integrity in noisy hospital environments, we utilize a Shielded Signal Repeater. This device is strategically placed to collect signals from distant wearables, filter out electromagnetic interference from heavy machinery, and securely forward the clean data to the Hub, ensuring that patient data remains protected.


