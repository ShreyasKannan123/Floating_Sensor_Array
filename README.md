# Floating_Sensor_Array

This project combines the power of ESP32 microcontrollers with specialized sensors to create a comprehensive data collection system. It's specifically designed to gather and transmit data from a pH sensor (SKU: 235871), a color sensor (GY-31 TCS3200), and a turbidity sensor (SKU: 62828) in aquatic environments. The project revolves around a 3D-printed boat fitted with an external battery and a custom PCB that integrates an ESP32 microcontroller alongside the mentioned sensors. The ESP32 actively collects data from these sensors and transmits it over a WiFi network for further analysis and monitoring.

## Components

- **ESP32 Microcontroller**: Manages data collection, processing, and WiFi transmission.
- **pH Sensor (SKU: 235871)**: Measures pH levels in the water.
- **Color Sensor (GY-31 TCS3200)**: Detects and categorizes colors in the environment.
- **Turbidity Sensor (SKU: 62828)**: Measures the cloudiness or turbidity of the water.
- **3D Printed Boat**: Serves as the platform for the sensors and the ESP32, enabling mobility and adaptability in aquatic environments.
- **External Battery**: Powers the entire system for extended operation.

## Files

- **CAD Files**: Contains the 3D design files for the boat.
- **PCB Files**: Includes designs and schematics for the integrated PCB.
- **Program**: Hosts the code that orchestrates sensor data collection, processing, and WiFi transmission.

## Purpose

This project aims to facilitate data collection in aquatic environments, enabling:

- **Environmental Monitoring**: Tracking pH levels, water clarity (turbidity), and color variations.
- **Research and Analysis**: Providing data for research purposes, such as studying aquatic ecosystems.
- **Remote Sensing**: Transmitting real-time data over WiFi for remote monitoring and analysis.

## Setup

To replicate or work on this project:

1. **Hardware Assembly**: Construct the 3D-printed boat, integrate the sensors and ESP32, and connect the external battery.
2. **Upload Program**: Upload the provided program to the ESP32.
3. **Connect to WiFi**: Configure the ESP32 to connect to a WiFi network for data transmission.

## Notes

- Ensure proper calibration of sensors for accurate data collection.
- Modify the program as needed for specific use cases or additional functionalities.
- Respect environmental guidelines and regulations when deploying the system in natural habitats.

## Acknowledgements

This project was co-created by:

https://github.com/Sherif-Granak
