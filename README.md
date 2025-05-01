# Project Anemone 🌊🦑  
**Smart Marine Co-Pilot System for Small & Medium-Scale Fishermen**

---

## 📌 Overview

Project Anemone is an open-source, affordable, and modular marine telemetry system built for the real-world needs of small and medium-scale fishermen. Designed to act as a digital co-pilot, it collects and displays critical environmental data using ESP32-S3 hardware and a Flutter-based mobile app.

---

## 🎯 Key Features

- 🌡️ Real-time environmental monitoring (temperature, humidity, water surface temp, etc.)
- 📍 GPS tracking and navigation overlay
- 📶 LoRa and BLE communication
- 📲 Mobile interface via Flutter (Kadalrasa app)
- 🔋 Energy-efficient for long-term use at sea
- 🧠 Smart assistant features (weather alerts, motion awareness, etc.)

---

## 🛠️ Tech Stack

| Layer       | Tools/Tech Used                         |
|-------------|------------------------------------------|
| Firmware    | ESP32-S3, Arduino Framework              |
| Sensors     | DHT22, DS18B20, MPU6050, BMP180, GPS     |
| Comms       | LoRa SX1278, BLE                         |
| Mobile App  | Flutter (Kadalrasa)                      |
| Display     | 0.96" OLED, RGB ring (WS2812)            |

---

## 📁 Folder Structure

```
project-anemone/
├── docs/               # Design, research & planning
├── firmware/           # ESP32 firmware code
├── flutter_app/        # Kadalrasa mobile app
├── hardware/           # Schematics & physical layout
└── README.md
```

---

## 🚀 Getting Started

### 1. Firmware Setup

- Platform: ESP32-S3
- Install: [ESP32 Arduino Core](https://docs.espressif.com/projects/arduino-esp32/)
- Libraries used:
  - Adafruit Sensor libraries
  - FastLED / NeoPixel
  - OneWire, DallasTemperature
  - TinyGPS++
  - LoRa by Sandeep Mistry

### 2. Flutter App (Kadalrasa)

```bash
cd flutter_app/kadalrasa
flutter pub get
flutter run
```

- Minimum SDK: Android 14
- BLE permissions required

---

## 🧪 Current Version

**v0.1** – Core sensors and BLE syncing are implemented.  
Upcoming: Weather forecast integration, comfort scoring, GPS path tracking.

---

## 🤝 Contributing

Pull requests are welcome! Feel free to fork and build upon the system for your own marine projects or fishing communities.

---

## 🪪 License

MIT License – Free for personal and commercial use with attribution.

---

## 💬 Contact

Made with love by [YourNameHere] ✨  
If you're a fisherman, researcher, or developer — reach out and let's collaborate!
