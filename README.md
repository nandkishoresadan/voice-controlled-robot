# VOCROID – Voice Controlled Robot

![Banner](assets/banner.png)

![Arduino](https://img.shields.io/badge/Arduino-Uno-blue?logo=arduino)
![Platform](https://img.shields.io/badge/Platform-Embedded-lightgrey)
![Bluetooth](https://img.shields.io/badge/Connectivity-Bluetooth-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)
[![Made by Heleena Robert](https://img.shields.io/badge/Made%20by-Heleena%20Robert-8A2BE2?style=flat-square)](https://github.com/HeleenaRobert)

## 📌 Overview  

**VOCROID** is a voice-controlled robot powered by Arduino Uno and the Adafruit Motor Shield.  
It uses the **HC-05 Bluetooth module** and an **Android device (AMR Voice app)** to receive voice commands and control the robot wirelessly.

This project demonstrates the integration of Arduino, Bluetooth communication, and motor control for robotics applications.

---

## 📂 Folder Structure

```Structure
vocroid-voice-controlled-robot/
│
├── vocroid/                # Main Arduino sketch
│   └── vocroid.ino
│
├── assets/                    # Project assets
│   ├── banner.png             # GitHub banner
│   ├── workflow.png           # System workflow diagram
│   └── vocroid.png
│
├── docs/                      # Documents (My Journal)
│   └── journal.pdf
│
├── README.md                  # Project documentation
├── requirements.txt           # Libraries used
├── LICENSE
└── .gitignore                 # Ignored files
```

---

## 🔧 Hardware Used  

- Arduino Uno  
- Adafruit L293D Motor Shield  
- HC-05 Bluetooth Module  
- 2x DC Motors (Chassis)  
- LED (status indicator)  
- 9V Battery with Connector  
- Jumper Wires
- Extra wheels for support  

---

## 🗂 System Workflow  

![Workflow Diagram](assets/workflow.png)

---

## 🎙 Voice Commands  

- `go` → Move forward  
- `back` → Move backward  
- `left` → Turn left  
- `right` → Turn right  
- `lights on` → Turn LED on  
- `lights off` → Turn LED off  
- `run` → Move forward continuously  
- `stop` → Stop movement  

---

## 🚀 Usage

1. Upload `vocroid.ino` to Arduino Uno.
2. Mount the Adafruit Motor Shield on Arduino.
3. Connect HC-05 Bluetooth module (VCC→5V, GND→GND, TX→RX, RX→TX).
4. Pair your Android phone with HC-05 (PIN: `1234` or `0000`).
5. Install **AMR Voice** app from Play Store.
6. Connect to HC-05 in the app and speak commands.

---

## 📦 Requirements  

- Arduino IDE  
- **AFMotor Library** (Adafruit Motor Shield)  

---

## 📷 Visual Example

VOCROID Sample
![Bot Example](assets/vocroid.png)

![AI Generated](https://img.shields.io/badge/AI%20Generated-%23CC5500?style=flat&logoColor=black&labelColor=CC5500&color=CC5500)

---

## 🔮 Future Enhancements  

- Add wireless camera for surveillance.  
- Upgrade to IoT control over Wi-Fi.  
- Integrate obstacle detection sensors.  

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 👩‍💻 Author

Developed by [Heleena Robert](https://github.com/HeleenaRobert)
