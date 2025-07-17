# Beacon Spam using ESP32

This project demonstrates how to send custom Wi-Fi beacon frames using an ESP32 board to simulate fake access points. It can be used for **educational**, **penetration testing**, or **Wi-Fi security awareness** purposes.

> ⚠️ For educational and ethical hacking purposes only. Do not use this code to disrupt networks without permission.

## 🔧 Features

- Sends multiple fake Wi-Fi access points (SSID spam)
- Easily customizable SSID list
- Lightweight and fast beacon frame generation using ESP32's low-level Wi-Fi functions

## 🧰 Requirements

- **ESP32** board (e.g., NodeMCU ESP32, DevKit V1, TTGO)
- Arduino IDE installed
- ESP32 board support added via the Arduino Board Manager
- [WiFi.h](https://github.com/espressif/arduino-esp32) and related dependencies

## 🚀 Getting Started

1. Connect your ESP32 to your PC.
2. Open `Beacon_Spam.ino` in the Arduino IDE.
3. Select the correct **Board** and **Port** from `Tools > Board` and `Tools > Port`.
4. Upload the sketch to the ESP32.
5. Open the Serial Monitor (baud rate: 115200) to view debug logs and SSID spam activity.

## 🛠️ How to Use

Follow these simple steps to run the Beacon Spam project on your ESP32:

### 🔌 1. Hardware Setup

- Use an **ESP32 board** (e.g., NodeMCU ESP32 or ESP32 DevKit)
- Connect it to your PC via a USB cable

### 💻 2. Software Setup

1. Install **Arduino IDE** from [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)
2. Add ESP32 board support:
   - Open `File > Preferences`
   - Paste the following URL into **Additional Boards Manager URLs**:
     ```
     https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
     ```
   - Then go to `Tools > Board > Boards Manager`, search for **ESP32**, and click **Install**
3. Restart Arduino IDE

### 📂 3. Get the Code

You can clone this repository directly using Git:

```bash
git clone https://github.com/CyberHulk7/beacon-spam.git
cd beacon-spam

## 📁 File Info

- `Beacon_Spam.ino` – Main code that performs beacon frame spam using ESP32 Wi-Fi APIs.
- `README.md` – Documentation of the project.

## 📜 License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this code, but only for **ethical** and **legal** activities.

## 📢 Disclaimer

This code is intended for **educational** and **research** purposes **only**. The author is **not responsible** for any misuse or damage caused by this code. Always get **explicit permission** before testing any network that you do not own.
