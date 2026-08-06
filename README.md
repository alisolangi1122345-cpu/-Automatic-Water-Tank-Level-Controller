# 🚰 Automatic Water Tank Level Controller

An Arduino Uno–based **Automatic Water Tank Level Controller** that monitors the water level using an **HC-SR04 Ultrasonic Sensor** and automatically controls a **12V DC water pump** through a relay module. The system displays real-time tank level and pump status on a **16×2 LCD**, preventing water overflow and dry running.



---

## ✨ Features

- 🚰 Automatic water pump ON/OFF control
- 📏 Real-time water level monitoring
- 📟 16×2 LCD status display
- ⚡ Relay-based pump control
- 🛡️ Prevents tank overflow
- 🔒 Protects pump from dry running
- 🔄 Fully autonomous operation
- 🔧 Easy to customize water level thresholds

---

## 🛠️ Hardware Used

| Component | Quantity |
|-----------|----------|
| Arduino Uno | 1 |
| HC-SR04 Ultrasonic Sensor | 1 |
| 1-Channel Relay Module | 1 |
| 16×2 LCD Display | 1 |
| 12V DC Water Pump | 1 |
| 12V Power Supply | 1 |
| Jumper Wires | As Required |
| Breadboard / PCB | 1 |

---

## ⚙️ Working Principle

1. The HC-SR04 continuously measures the distance between the sensor and the water surface.
2. Arduino calculates the water level percentage.
3. The current water level is displayed on the LCD.
4. When the water level falls below the predefined threshold:
   - The relay turns the water pump **ON**.
5. When the tank becomes full:
   - The relay automatically turns the pump **OFF**.
6. The system continuously repeats the monitoring process.

---


---

## 💻 Software

- Arduino IDE
- Embedded C/C++
- Proteus 

---


---

## 🚀 Future Improvements

- ESP32 IoT Monitoring
- Mobile App Integration
- Blynk Dashboard
- Wi-Fi Notifications
- Water Consumption Analytics
- OLED Display Support

---

## 📄 License

This project is released under the **MIT License**.

---

## 👨‍💻 Author

**Ali Nawaz**

- Electrical Engineering Student
- Embedded Systems & PCB Design Enthusiast

GitHub:
https://github.com/alisolangi1122345-cpu

LinkedIn:
(Add your LinkedIn profile here)

---
⭐ If you found this project helpful, don't forget to star the repository.
