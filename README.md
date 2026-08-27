<img width="300" alt="Track_Freelander" src="https://github.com/user-attachments/assets/b3fa5977-0cea-4749-bc14-8773b1c06a87" />
# OBD-II-Telemetry-Freelander2
OBD-II vehicle telemetry system using ESP32, Bluetooth ELM327, and GPS Neo-6M. Real-time monitoring of RPM, boost, speed, coolant temp, and fuel level.

# OBD-II Telemetry System for Freelander 2 Diesel

Automotive telemetry system developed in C++/Arduino for real-time monitoring of a diesel vehicle.

## Features

**SAE J1979 PID Reading:**
- Engine RPM (010C)
- Turbo/MAP Pressure (010B)
- Vehicle Speed ​​(010D)
- Coolant Temperature (0105)
- Fuel Level (012F)
- Battery Voltage (ATRV)

**GPS Integration:**
- Coordinate logging (Neo-6M)
- Satellite-based speed
- Precise timestamp

**Graphical Interface:**
- 3.5" TFT Display (ESP32 CYD)
- 3x2 layout with contextual data fields
- Real-time updates

**Robustness:**
- Automatic Bluetooth reconnection
- Watchdog timer for system recovery
- SD card logging

## ️ Hardware

- **MCU:** ESP32-2432S028R (CYD)
- **Communication:** Bluetooth Serial (HC-05/HC-06)
- **GPS:** Neo-6M
- **OBD-II Adapter:** ELM327 Bluetooth
- **Storage:** 1GB SD Card

## Screenshots

Photos coming soon

## Demo

YouTube video link coming soon

## 📄 License

MIT License - free for personal and commercial use
