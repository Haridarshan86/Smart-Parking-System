# 🚗 Smart Parking & Vehicle Entry System

<p align="center">
  <img width="100%" src="https://github.com/user-attachments/assets/3bbd62b7-e8bf-467b-9d89-2c50f93cb748" alt="Smart Parking Dashboard">
</p>

<h1 align="center">Smart Parking & Vehicle Entry System</h1>

<p align="center">
An IoT-Based Smart Parking Solution using <strong>ESP32</strong>, <strong>RFID</strong>, <strong>MQTT</strong>, <strong>ThingSpeak</strong>, and <strong>Twilio</strong> for automated vehicle entry, occupancy monitoring, cloud analytics, and real-time alerts.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-IoT-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/RFID-Authentication-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/MQTT-Real--Time-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/ThingSpeak-Cloud-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Twilio-SMS-purple?style=for-the-badge">
</p>

---

## 📖 Overview

Parking congestion is one of the major challenges in modern cities. This project presents an IoT-powered Smart Parking and Vehicle Entry System that automates parking operations and provides real-time monitoring through cloud technologies.

The system integrates:

* 🔐 RFID Authentication
* 🚗 Automated Vehicle Entry & Exit
* 📡 MQTT Communication
* 🚦 IR Sensor Occupancy Detection
* ☁️ ThingSpeak Cloud Visualization
* 📱 Twilio SMS Notifications
* 🌐 Interactive Web Dashboard

---

## ✨ Key Features

✅ RFID-Based Vehicle Authentication

✅ Real-Time Parking Slot Monitoring

✅ Automated Vehicle Entry & Exit

✅ Occupancy Detection using IR Sensors

✅ MQTT-Based Live Communication

✅ ThingSpeak Cloud Analytics

✅ SMS Alerts using Twilio

✅ Interactive Web Dashboard

✅ Automated Parking Fee Deduction

✅ Event Logging & Monitoring

---

## 🏗️ System Architecture

```text
                 RFID Reader
                      │
                      ▼
                   ESP32
                      │
         ┌────────────┼────────────┐
         │            │            │
         ▼            ▼            ▼
       MQTT      ThingSpeak      Twilio
         │            │            │
         ▼            ▼            ▼
    Dashboard     Analytics    SMS Alerts
```

---

## ⚙️ Hardware Components

| Component           | Purpose                 |
| ------------------- | ----------------------- |
| ESP32               | Main Controller         |
| MFRC522 RFID Module | Vehicle Authentication  |
| IR Sensor           | Vehicle Detection       |
| Green LED           | Vacant Slot Indicator   |
| Red LED             | Occupied Slot Indicator |
| Breadboard          | Prototyping             |
| Jumper Wires        | Connections             |
| Power Supply        | System Power            |

---

## 💻 Software Stack

| Technology  | Purpose                   |
| ----------- | ------------------------- |
| Arduino IDE | ESP32 Programming         |
| MQTT        | Real-Time Communication   |
| ThingSpeak  | Cloud Storage & Analytics |
| Twilio      | SMS Notifications         |
| HTML        | Frontend Development      |
| CSS         | User Interface Styling    |
| JavaScript  | Dashboard Logic           |
| Node.js     | Backend Services          |

---

## 🔄 Working Principle

### 🚘 Vehicle Entry

1. User scans RFID card.
2. ESP32 verifies the UID.
3. Slot availability is checked.
4. Entry is granted if a slot is available.
5. Event is logged and published.

### 🚦 Occupancy Detection

* IR sensor continuously monitors parking occupancy.
* Green LED indicates a vacant slot.
* Red LED indicates an occupied slot.

### ☁️ Cloud Communication

* Data transmitted via MQTT.
* ThingSpeak stores and visualizes parking statistics.

### 📱 Notification System

* Parking Full Alert
* Unauthorized RFID Alert
* Exit Confirmation Message

### 📊 Dashboard Updates

* Live Occupancy Status
* Parking Layout Visualization
* Occupancy Percentage
* Activity Logs

---

# 📸 Project Gallery

## 🌐 Smart Parking Dashboard

<p align="center">
<img width="100%" src="https://github.com/user-attachments/assets/3bbd62b7-e8bf-467b-9d89-2c50f93cb748" alt="Dashboard">
</p>

The dashboard displays live parking information, occupancy percentage, available slots, MQTT status, and parking activity logs.

---

## ☁️ ThingSpeak Cloud Analytics

<p align="center">
<img width="100%" src="https://github.com/user-attachments/assets/a29cad8b-816e-4d7a-a6a1-1486a52a7438" alt="ThingSpeak Analytics">
</p>

ThingSpeak provides cloud-based visualization of parking occupancy, entry events, and exit events.

---

## 🔧 Hardware Prototype

<p align="center">
<img width="45%" src="https://github.com/user-attachments/assets/9fcb15ee-5bfb-462e-8720-4181b547e9a5" alt="Hardware Setup">
</p>

Hardware implementation using ESP32, MFRC522 RFID module, IR sensor, LEDs, and Wi-Fi connectivity.

---

## 💳 Exit Payment Notification

<p align="center">
<img width="35%" src="https://github.com/user-attachments/assets/3bb16ca9-4b1d-46a8-8d10-eb86ee82a96e" alt="Payment SMS">
</p>

SMS confirmation sent when a vehicle exits and parking charges are deducted.

---

## 🚫 Parking Full Alert

<p align="center">
<img width="35%" src="https://github.com/user-attachments/assets/f28fb9e1-f444-4b21-8c31-e1aa1693cbfe" alt="Parking Full SMS">
</p>

Automatic SMS alert generated when the parking slot becomes unavailable.

---

## 🔐 Unauthorized RFID Alert

<p align="center">
<img width="35%" src="https://github.com/user-attachments/assets/5d9fa736-cbd3-4985-8896-cafc6d4e828b" alt="Unauthorized RFID Alert">
</p>

Security notification sent when an unauthorized RFID card is detected.

---

## 🖥️ Serial Monitor Output

<p align="center">
<img width="70%" src="https://github.com/user-attachments/assets/b01f4e8e-00a7-43e1-94fe-38e081be7b4d" alt="Serial Monitor">
</p>

ESP32 serial output showing RFID authentication, slot detection, MQTT publishing, and system logs.

---

## 🔄 System Flowchart

<p align="center">
<img width="50%" src="https://github.com/user-attachments/assets/c7732976-3d60-4cf2-a1dd-50762d7745e4" alt="Flowchart">
</p>

Complete workflow of the Smart Parking and Vehicle Entry System.

---

## 📊 Results

The system successfully achieved:

* Secure RFID Authentication
* Automated Vehicle Entry & Exit
* Real-Time Occupancy Monitoring
* MQTT-Based Communication
* Cloud Analytics with ThingSpeak
* SMS Notifications using Twilio
* Live Dashboard Monitoring
* Event Logging and Analytics

---

## 📂 Repository Structure

```bash
smart-parking-system/
│
├── firmware/
│   └── SmartParking.ino
│
├── dashboard/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── server/
│   └── server.js
│
├── images/
│
├── docs/
│
└── README.md
```

---

## 🚀 Future Enhancements

* Multi-Slot Parking Management
* Multi-Floor Parking Support
* Mobile Application Integration
* Online Slot Reservation
* AI-Based Parking Analytics
* Digital Payment Gateway
* Smart City Deployment

---

## 🎯 Applications

* Smart Cities
* Shopping Malls
* Residential Communities
* Educational Institutions
* Corporate Campuses
* Commercial Parking Facilities

---

## ⭐ Technologies Used

<p align="center">

ESP32 • RFID • MQTT • ThingSpeak • Twilio • HTML • CSS • JavaScript • Node.js • IoT

</p>

---

## 📜 License

This project is intended for educational and research purposes in the field of IoT and Smart Parking Systems.

---

<p align="center">
  Made with ❤️ using IoT Technologies
</p>

<p align="center">
⭐ If you found this project useful, consider starring the repository.
</p>
