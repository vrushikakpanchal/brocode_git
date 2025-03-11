# UnPlugged 2.0 - Smart City Sentinel

## Overview
This project was developed as part of **UnPlugged 2.0**, a 24-hour hardware hackathon organized by Shri Vile Parle Kelavani Mandal's Dwarkadas J. Sanghvi College of Engineering. Our solution focuses on **AI-driven IoT & GIS-based urban intelligence** to optimize traffic management, environmental monitoring, and public safety.

## Problem Statement
With rapid urbanization, cities face challenges in managing infrastructure, optimizing resources, and ensuring public safety. Existing systems often react too slowly, leading to inefficiencies. Our task was to **engineer an autonomous system** integrating:
- **IoT-based urban monitoring**
- **Multi-sensor data fusion**
- **Geographic Information System (GIS)**
- **AI models for traffic control, emergency response, and environmental monitoring**
- **Decentralized edge AI for real-time decision-making**

## Solution Implemented
### **1. Traffic Flow Optimization** 🚦
- **ESP32 cameras** placed across **4 lanes** to monitor vehicle density.
- AI logic to **prioritize lane clearance** based on congestion levels.

### **2. Environmental Monitoring** 🌍
- Hardware setup includes sensors for **AQI, dust, and temperature levels**.
- Data is **transmitted in real-time** to a **cloud-based dashboard**.

### **3. User Dashboard & Access** 🖥️
- **Two types of logins:**
  - **Admin (Traffic Police):** Controls signal timings.
  - **User:** Accesses live traffic updates and environmental data.
- **Web-based dashboard** for real-time monitoring.

## Tech Stack & Components
- **Hardware:** ESP32-CAM, air quality sensors, temperature sensors, solar-powered PCB
- **Software:** KiCad (PCB design), Python, Flask, React.js
- **Cloud & AI:** Firebase, Edge AI for anomaly detection

## Team Members 👥
- @Vrushika Panchal [Diploma - AI/ML]
- @Harsh Pandey [B.Tech - EXTC]
- @Soham Nagvekar [B.Tech - EXTC]
- @Prasad Rane [B.Tech - EXTC]
- @Atharva Wadekar [B.Tech - EXTC]
- @Advait Shinde [Diploma - AI/ML]

## Repository Structure
```
📂 brocode_git
 ┣ 📂 01_Kicad_PCB        # KiCad PCB designs
 ┣ 📂 02_GERBER           # ESP32 & IoT sensor integration
 ┣ 📂 03_project_images           # React.js frontend for monitoring
 ┣ 📂 04_frontend_website               # Traffic analysis & anomaly detection
 ┣ 📜 README.md               # Project documentation
```

