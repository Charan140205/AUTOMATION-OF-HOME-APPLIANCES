# 🏠 Automation of Home Appliances Using Arduino & Bluetooth

An Arduino-based Home Automation System that enables users to wirelessly control household appliances such as lights and fans using an Android smartphone via Bluetooth. This project offers a simple, low-cost, and efficient smart home solution for remote appliance control.

---

## 📌 Overview

Traditional wall switches require users to manually operate electrical appliances. This project replaces conventional control with a Bluetooth-based wireless system. An Android smartphone sends commands to an HC-05 Bluetooth module connected to an Arduino Uno, which controls appliances through a relay module.

---

## ✨ Features

- 📱 Control home appliances using an Android smartphone
- 🔵 Bluetooth communication using HC-05 module
- 💡 Switch lights, fans, and other appliances ON/OFF
- ⚡ Low-cost and easy-to-build solution
- 🔌 Supports multiple appliances using relay modules
- 🛠 Beginner-friendly Arduino project

---

## 🛠 Hardware Components

- Arduino Uno
- HC-05 Bluetooth Module
- 2-Channel Relay Module
- 5V Power Supply
- Connecting Wires
- AC Bulb / Fan (Load)
- Android Smartphone

---

## 💻 Software Used

- Arduino IDE
- Arduino C++
- Bluetooth Controller / Bluetooth Terminal App

---

## ⚙️ Working Principle

1. Pair the Android smartphone with the HC-05 Bluetooth module.
2. Open a Bluetooth Controller application.
3. Send ON/OFF commands from the smartphone.
4. Arduino receives the commands through serial communication.
5. The relay module switches the connected appliances ON or OFF.

---

## 📲 Bluetooth Commands

| Command | Action |
|:-------:|--------|
| **1** | Turn ON Appliance 1 |
| **2** | Turn OFF Appliance 1 |
| **3** | Turn ON Appliance 2 |
| **4** | Turn OFF Appliance 2 |

---

## 📂 Repository Structure

```
AUTOMATION-OF-HOME-APPLIANCES
│
├── HomeAutomation.ino
├── HOME_AUTOMATION.pdf
├── HOME_AUTOMATION.png
└── README.md
```

---

## 🚀 Future Enhancements

- Wi-Fi-based home automation using ESP8266/ESP32
- IoT cloud monitoring
- Voice control using Google Assistant or Alexa
- Mobile application with a custom user interface
- Timer and scheduling features
- Energy consumption monitoring

---

## 📄 Project Report

The complete project documentation is available in:

**HOME_AUTOMATION.pdf**

---

## 🖼️ Circuit Diagram

The circuit diagram for this project is available in:

**HOME_AUTOMATION.png**

---

## 👨‍💻 Author

**Charan**

Electronics and Communication Engineering Student

GitHub: **https://github.com/Charan140205**

---

## 📜 License

This project is developed for educational and learning purposes.
