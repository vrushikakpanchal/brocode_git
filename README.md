# UNPLUGGED 2.0 - 24-Hour Hardware Hackathon
## Round 2 Submission

### Team Brocode
- Harsh Pandey [B.Tech - EXTC]
- Soham Nagvekar [B.Tech - EXTC]
- Prasad Rane [B.Tech - EXTC]
- Atharva Wadekar [B.Tech - EXTC]
- Advait Shinde [Diploma - AI ML]
- Vrushika Panchal [Diploma - AI ML]

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Introduction](#introduction)
3. [Project Overview](#project-overview)
4. [Design Verification](#design-verification)
5. [Hardware Implementation](#hardware-implementation)
6. [Component List](#component-list)
7. [PCB Layout](#pcb-layout)
8. [Enclosure Design](#enclosure-design)
9. [Documentation](#documentation)
10. [Final Product](#final-product)
11. [GitHub Repository](#github-repository)

## Problem Statement

With rapid urbanization, real-time environmental monitoring has become essential for sustainable city planning. The **Smart City Sentinel** project addresses this need by developing a modular PCB that integrates sensors, power management, and communication protocols. This enables seamless data collection and transmission, ensuring efficient environmental surveillance in urban areas.

## Introduction

The **Smart City Sentinel** project focuses on designing a modular PCB using **KiCad** to facilitate real-time environmental monitoring. The PCB incorporates **sensor interfacing, power management, and efficient data transmission** within a scalable and optimized architecture. Adhering to competition constraints, the design features a **two-layer PCB**, **standardized components**, and **optimized connectivity**, ensuring seamless functionality and future scalability.

## Project Overview

The **Smart City Sentinel** is an advanced modular PCB designed for intelligent environmental surveillance. It integrates:

- Multiple environmental sensors for comprehensive data collection
- Robust power management system with solar panel support for sustainable operation
- Structured communication protocols for reliable data transmission
- Modular design architecture allowing future enhancements with minimal modifications

The system strictly adheres to power and connectivity constraints while maintaining optimal performance. Additionally, a precision-engineered 3D CAD model ensures seamless structural integration with the predefined solar panel, enhancing practical usability and real-world implementation potential.

## Design Verification

### Electrical Rule Check (ERC) and Design Rule Check (DRC)

![ERC and DRC Verification](media/image1.jpeg)

All design and electrical rule checks have been successfully passed, ensuring the PCB meets industry standards for manufacturing and electrical performance.

The component placement has been optimized for:
- Minimal signal interference
- Efficient power distribution
- Thermal management
- Logical grouping of functional components

## Component List

### Bill of Materials (BOM)

| Component | Quantity | Price (₹) |
|-----------|----------|-----------|
| ESP32-53 Dev module | 1 | 1,458.00 |
| MQ-135 Gas Sensor | 1 | 139.00 |
| Sound Sensor Module | 1 | 37.00 |
| OLED Display | 1 | 289.00 |
| BME280 Environmental Sensor | 1 | 44.00 |
| Solar Panel | 1 | 189.00 |
| Rechargeable Module (TP4056) | 1 | 24.00 |
| IR Flame Sensor | 1 | 69.00 |
| Battery 3.7v 2500mAh 18560 | 1 | 800.00 |
| Voltage Booster | 1 | 49.00 |
| Dust Sensor | 1 | 599.00 |
| Hall Effect Sensor | 1 | 34.00 |
| MAX471 Current and Voltage Sensor | 1 | 399.00 |
| Water Flow Sensor | 1 | 236.00 |
| DHT11 Temperature and Humidity Sensor | 1 | 90.00 |
| Soil Moisture Sensor | 1 | 189.00 |
| Relay Module | 1 | 199.00 |
| Rain Sensor | 1 | 156.00 |
| RTC DS3231 module | 1 | 122.00 |
| **TOTAL** | | **5,122.00** |

The custom 3D-printed enclosure is designed to:
- Protect the ESP32-S3 and camera module for traffic rule monitoring
- Provide strategically placed cutouts for wiring, ventilation, and the camera lens
- Feature a secure screw-on bottom cover for easy maintenance access
- Ensure durability in outdoor environments
- Maintain stable positioning for reliable image capture and processing

## Documentation

**SmartCity-Sentinel-PCB**: A modular PCB designed for real-time environmental monitoring. Our repository contains:
- Complete schematic files
- PCB layout designs
- 3D CAD models
- Comprehensive project documentation
- Installation and usage guides

---

© 2025 Team Brocode | UNPLUGGED 2.0 Hardware Hackathon
