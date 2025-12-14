# ESP32-S3-XR-Glasses-PCB
Custom PCB with ESP32-S3 camera module for AI/XR glasses
# ESP32-S3 Camera Resolution Performance Demo

## Project Overview
This project demonstrates video capture using an ESP32-S3-based camera system at multiple
resolutions to study trade-offs between image quality, frame rate, and memory usage.
The system is intended for compact, wearable AI/XR applications.

## Hardware
- ESP32-S3 MCU
- Camera module (OV2640 / OV3660)
- External PSRAM (on-chip)
- USB power and programming interface

## Software
- Arduino framework
- ESP32 camera driver

## Demo Description
Video clips were captured at different resolutions supported by the ESP32-S3:
- 320×240 (QVGA)
- 640×480 (VGA)
- 800×600 (SVGA)

Each configuration was evaluated for visual quality and approximate frame rate.

## Results
Lower resolutions achieved higher frame rates and stability, while higher resolutions
provided improved image detail at the cost of increased memory usage and reduced frame rate.

## Repository Structure
- firmware/: ESP32-S3 camera firmware
- hardware/: Schematic and PCB layout
- results/: Recorded video samples and performance logs
- report/: Final project report (PDF)

## Demo Video
YouTube link: [https://youtu.be/lZMv0Ex0UyA]

## Author
Supriya Ramaswamy  
EECE – Wireless & Network Engineering
