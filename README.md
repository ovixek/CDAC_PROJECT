# CDAC_PROJECT

Monorepo for the **Vehicle Safety System using CAN and IoT**, developed as part of CDAC.

## Project Overview
This project implements a distributed vehicle safety system using the CAN protocol.
Multiple STM32 nodes communicate critical sensor data, and an IoT node enables cloud monitoring.

## Repository Structure

### 🔹 HAL_CAN_TX (Sensor Node)
- STM32-based CAN transmitter
- Collects sensor data
- Sends data over CAN bus

### 🔹 HAL_CAN_RX (Processing Node)
- STM32-based CAN receiver
- Processes incoming CAN frames
- Acts as central processing unit
- Cloud Connectivity

## Tools & Technologies
- STM32F4 Series
- STM32CubeIDE
- CAN Protocol
- Embedded C

## Notes
- Only source and configuration files are added
---
