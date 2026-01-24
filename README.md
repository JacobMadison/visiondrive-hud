# VisionDrive – Intelligent Head-Up Display Prototype

VisionDrive is an intelligent, modular, and fully retrofit-capable head-up display (HUD) prototype designed to improve road safety by reducing driver distraction. The system projects essential driving and environmental information directly into the driver’s primary field of view.

The project was developed as part of a diploma thesis and submitted to national innovation competitions, including Jugend Innovativ and the Bosch Innovationspreis.

---

## 🚗 Project Overview

Modern vehicles present drivers with an increasing amount of digital information, often requiring visual attention away from the road. VisionDrive addresses this challenge by combining embedded electronics, real-time software, and automated mechanics into a single integrated assistance system.

**Key features include:**
- Real-time GPS-based speed display
- Environmental monitoring (temperature & air quality)
- ESP32-based embedded system
- Automated, servo-driven HUD deployment mechanism
- Modular and vehicle-independent design

---

## 🔧 System Architecture

VisionDrive consists of three main subsystems:
- **Electronics & Sensors** (ESP32, GPS, temperature and air-quality sensors)
- **Embedded Software** (real-time data processing and display logic)
- **Mechanical System** (automated deployment of the projection surface)

The system is designed to be extensible and suitable for further development toward a market-ready product.

---

## 🛠️ Hardware Components

- ESP32 microcontroller
- NEO-6M GPS module
- DHT11 / DHT22 temperature sensor
- MQ135 air quality sensor
- OLED display (SSD1306)
- Servo motor for automated deployment

---

## 💻 Software

The firmware is written for the ESP32 platform using the Arduino framework.  
It handles:
- Sensor data acquisition
- Data filtering and prioritization
- Display rendering
- Servo control logic

The codebase is structured to allow easy expansion and adaptation.

---

## 📁 Repository Structure

