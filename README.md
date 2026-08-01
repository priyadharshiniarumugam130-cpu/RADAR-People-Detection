# Radar People Detection using TI AWR1843

## Overview
This project implements a real-time people detection system using the TI AWR1843 mmWave radar. The radar detects people by estimating their distance, velocity, and position (X, Y, Z coordinates). A Python application communicates with the radar through UART, processes the received data, and displays the detected targets.

## Features
- Real-time people detection
- Distance and velocity estimation
- X, Y, Z coordinate extraction
- UART communication with AWR1843
- Python-based radar data processing
- Real-time target visualization

## Hardware Used
- TI AWR1843 mmWave Radar
- USB Cable
- Windows PC/Laptop

## Software Used
- Python 3.x
- TI mmWave SDK
- Tera Term / Demo Visualizer (for configuration)
- Visual Studio Code / IDLE

## Project Structure
```
Radar-People-Detection/
├── src/
├── config/
├── images/
├── README.md
└── requirements.txt
```

## How to Run
1. Connect the TI AWR1843 radar to the PC.
2. Update the CLI and Data COM port numbers in the Python script.
3. Load the radar configuration (.cfg) file.
4. Run the Python program.
5. View the detected targets in real time.

## Applications
- Smart Surveillance
- Occupancy Monitoring
- Industrial Safety
- Smart Buildings
- Human Presence Detection

## Author
Priya Dharshini
