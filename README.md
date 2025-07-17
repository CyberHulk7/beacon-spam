# Beacon Spam using ESP32

This project demonstrates how to send custom Wi-Fi beacon frames using an ESP32 board to simulate fake access points. It can be used for **educational**, **penetration testing**, or **Wi-Fi security awareness** purposes.

> ⚠️ For educational and ethical hacking purposes only. Do not use this code to disrupt networks without permission.

---

## 🔧 Features

- Sends multiple fake Wi-Fi access points (SSID spam)
- Easily customizable SSID list
- Lightweight and fast beacon frame generation using ESP32's low-level Wi-Fi functions

---

## 🧰 Requirements

- **ESP32** board (e.g., NodeMCU ESP32, DevKit V1, TTGO)
- Arduino IDE installed
- ESP32 board support added via the Arduino Board Manager
- Basic knowledge of how to flash a sketch to the ESP32
- [WiFi.h](https://github.com/espressif/arduino-esp32) and related dependencies

---

## 🚀 Getting Started

1. Connect your ESP32 to your PC.
2. Open `Beacon_Spam.ino` in the Arduino IDE.
3. Select the correct **Board** and **Port** from `Tools > Board` and `Tools > Port`.
4. Click the **Upload** button to flash the sketch to ESP32.
5. Open the Serial Monitor (baud rate: 115200) to view debug logs and SSID spam activity.

---

## 🧪 Installation & Setup

Follow the steps below to install and run the project on your ESP32 board.

###  Clone the Repository

```bash
git clone https://github.com/CyberHulk7/beacon-spam.git
cd beacon-spam
