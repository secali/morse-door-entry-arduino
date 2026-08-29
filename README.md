# 🔐 Morse Code Door Entry System (Arduino)

[![C++](https://img.shields.io/badge/C%2B%2B-Embedded-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![Arduino](https://img.shields.io/badge/Hardware-Arduino%20Uno-00979D?style=flat-square&logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![Security](https://img.shields.io/badge/Access%20Control-Frequency%20Pattern-green?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

> **Arduino-powered access control system with audio frequency recognition and Morse sequence pattern matching for automated electronic door strikes.**

---

## 🎯 Overview

An innovative hardware access control mechanism that decodes custom acoustic knock/frequency pulses using Morse code timing logic (dots and dashes). Upon detecting the correct pre-programmed passcode sequence within configured timing tolerances, the microcontroller activates an electronic relay connected to a door strike mechanism.

### 🌟 Key Features
- **Adaptive Pulse Duration Detection**: Distinguishes between dots (short pulses) and dashes (long pulses) using calibrated millisecond thresholds.
- **Audio / Piezo Sensor Integration**: Reads acoustic signals via microphone or piezoelectric vibration sensor.
- **Fail-Safe Lockout Logic**: Automatic lockout after sequential invalid attempts with visual LED warning cues.

---

## 🔌 Circuit Connection & Testing

- Review `Scheme-Testing-on-Arduino-Uno.png` for complete breadboard and relay schematics.
- Upload `Open-Door-Morse-rev1.ino` to your Arduino Uno board.


---

## 👨‍💻 Author & Professional Profile

**Sergio Cañete Linares**  
*Senior QA Automation Engineer (SDET) | Software Developer in Test & AI-Driven Testing*

Specializing in scalable test automation architectures, microservices API testing, event-driven systems (Kafka), custom MCP servers, and multi-agent AI testing orchestration.

- 💼 **LinkedIn**: [linkedin.com/in/secali](https://www.linkedin.com/in/secali)
- 🐙 **GitHub**: [@secali](https://github.com/secali)
- 📧 **Email**: [sergio13896@gmail.com](mailto:sergio13896@gmail.com)
- 📍 **Location**: Spain
