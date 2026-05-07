# 🚗 Smart Parking System (Arduino)

## 📌 Overview
This project is a Smart Parking System built using Arduino.  
The system automatically detects vehicles, controls a gate mechanism, and shows parking availability using LEDs. It also includes a sound alert when the gate opens.

---

## ⚙️ Features

- 🚧 Automatic gate opening when a vehicle is detected
- 🔦 Light sensor detection (placed before the barrier)
- 🔁 Motor-controlled barrier system
- 🟢🔴 Parking availability indicator:
  - Green LED → parking spot available
  - Red LED → parking spot occupied
- 🔊 Sound alert when the gate opens

---

## 🧠 How It Works

1. A vehicle approaches the entrance.
2. The sensor detects the vehicle (light change / obstruction).
3. The motor activates and opens the barrier automatically.
4. A buzzer produces a sound during gate movement.
5. LED indicator updates parking status:
   - Green = available
   - Red = full

---

## 🧩 Components Used

- Arduino Uno
- Light / IR sensor
- Servo motor / DC motor (gate mechanism)
- Red & Green LEDs
- Buzzer / speaker
- Resistors, wires, breadboard

---

## 🖼️ Project Images

### 📷 Parking System Overview
![Parking System](https://github.com/user-attachments/assets/e9b9ff9f-765b-4844-9852-3f588bd9478f)


### 📷 Gate Mechanism / Circuit
![Circuit Setup](https://github.com/user-attachments/assets/eeaccdba-17a4-428b-9f3e-227f2c2560bf)


---

## 🚀 Future Improvements

- Mobile app for parking monitoring
- Individual slot detection sensors
- Smart payment system integration
- IoT-based remote control

---

## 👩‍💻 Team

Developed as part of a two-person academic project, with primary responsibility for system design, implementation, and hardware integration.

Sari Getzel & Avigail Rappaport
