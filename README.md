
# 🚗 Smart Parking & Vehicle Entry System

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-IoT-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/RFID-Authentication-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/MQTT-Real--Time-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/ThingSpeak-Cloud-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Twilio-SMS-purple?style=for-the-badge">
</p>

<p align="center">
  An IoT-powered Smart Parking Solution for Automated Vehicle Entry, Occupancy Monitoring, Cloud Visualization, and Real-Time Alerts.
</p>

---

## 📖 Overview

Managing parking spaces efficiently is a growing challenge in modern cities.

This project introduces an **IoT-Based Smart Parking and Vehicle Entry System** that automates vehicle authentication, monitors parking occupancy in real-time, visualizes data on the cloud, and sends instant alerts to users.

The system combines:

* 🔐 RFID Authentication
* 📡 MQTT Communication
* ☁️ ThingSpeak Cloud Analytics
* 📲 Twilio SMS Notifications
* 🚦 Real-Time Slot Monitoring
* 🌐 Interactive Web Dashboard

---

## ✨ Key Features

✅ RFID-Based Vehicle Entry & Exit

✅ Real-Time Parking Slot Monitoring

✅ Occupancy Detection using IR Sensors

✅ MQTT-Based Live Communication

✅ ThingSpeak Cloud Visualization

✅ SMS Alerts using Twilio

✅ Dynamic Web Dashboard

✅ Automatic Parking Fee Management

✅ Event Logging & Analytics

---

## 🏗️ System Architecture

```text
RFID Reader
      │
      ▼
    ESP32
      │
 ┌────┼────┐
 │    │    │
 ▼    ▼    ▼
MQTT ThingSpeak Twilio
 │       │       │
 ▼       ▼       ▼
Dashboard Graphs SMS Alerts
```

---

## ⚙️ Hardware Components

| Component           | Description            |
| ------------------- | ---------------------- |
| ESP32               | Main Controller        |
| MFRC522 RFID Module | Vehicle Authentication |
| IR Sensor           | Occupancy Detection    |
| Red LED             | Occupied Indicator     |
| Green LED           | Vacant Indicator       |
| Breadboard          | Prototyping            |
| Power Supply        | System Power           |

---

## 💻 Software Stack

| Technology          | Purpose                       |
| ------------------- | ----------------------------- |
| Arduino IDE         | ESP32 Programming             |
| MQTT                | Real-Time Communication       |
| ThingSpeak          | Cloud Storage & Visualization |
| Twilio              | SMS Notifications             |
| HTML/CSS/JavaScript | Dashboard Development         |
| Node.js             | Backend Services              |

---

## 🔄 Workflow

### 1️⃣ Vehicle Entry

* User scans RFID card
* ESP32 verifies authentication
* Slot availability checked
* Entry granted if slot is available

### 2️⃣ Parking Detection

* IR sensor monitors slot occupancy
* Green LED → Vacant
* Red LED → Occupied

### 3️⃣ Data Transmission

* Status published via MQTT
* Cloud updated using ThingSpeak

### 4️⃣ Notifications

* Parking Full Alert
* Unauthorized RFID Detection
* Exit Confirmation SMS

### 5️⃣ Dashboard Update

* Live Occupancy Status
* Parking Layout Visualization
* Activity Logs
* Occupancy Statistics

---

## 🌐 Dashboard Features

### 📊 Live Overview

* Total Slots
* Available Slots
* Occupied Slots
* Occupancy Rate

### 🚗 Parking Layout

Visual representation of parking spaces with live updates.

### 📡 MQTT Integration

Connect and monitor real-time parking events.

### ☁️ ThingSpeak Analytics

Visualize occupancy trends and parking activity.

### 📱 SMS Notifications

Receive alerts instantly using Twilio.

---

## 📈 Results

The system successfully achieved:

* Real-Time Occupancy Detection
* Secure RFID Authentication
* Cloud-Based Monitoring
* Automated Event Logging
* SMS Alert Generation
* Interactive Dashboard Visualization

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

* Multi-Slot Deployment
* Multi-Floor Parking Support
* Mobile Application
* Online Reservation System
* AI-Based Parking Analytics
* Digital Payment Gateway
* Smart City Integration

---

## 📸 Project Screenshots

### Dashboard

```md
![Dashboard]
<img width="1600" height="813" alt="webpage2" src="https://github.com/user-attachments/assets/3bbd62b7-e8bf-467b-9d89-2c50f93cb748" />


```

### Hardware Setup

```md
![Hardware]

<img width="918" height="1353" alt="setup" src="https://github.com/user-attachments/assets/9fcb15ee-5bfb-462e-8720-4181b547e9a5" />
```

### ThingSpeak Visualization

```md
![ThingSpeak]
<img width="1600" height="773" alt="webpage1" src="https://github.com/user-attachments/assets/a29cad8b-816e-4d7a-a6a1-1486a52a7438" />

<img width="1080" height="684" alt="payment sms" src="https://github.com/user-attachments/assets/3bb16ca9-4b1d-46a8-8d10-eb86ee82a96e" />


<img width="1080" height="434" alt="slotfull sms" src="https://github.com/user-attachments/assets/f28fb9e1-f444-4b21-8c31-e1aa1693cbfe" />


<img width="1080" height="498" alt="unauthorised sms" src="https://github.com/user-attachments/assets/5d9fa736-cbd3-4985-8896-cafc6d4e828b" />


<img width="1042" height="704" alt="serial monitor" src="https://github.com/user-attachments/assets/b01f4e8e-00a7-43e1-94fe-38e081be7b4d" />


<img width="853" height="1280" alt="flowchart image" src="https://github.com/user-attachments/assets/c7732976-3d60-4cf2-a1dd-50762d7745e4" />

```

---

## 🎯 Applications

* Smart Cities
* Shopping Malls
* Residential Complexes
* Corporate Campuses
* Educational Institutions
* Commercial Parking Facilities

---

## ⭐ Technologies Used

ESP32 • RFID • MQTT • ThingSpeak • Twilio • HTML • CSS • JavaScript • Node.js • IoT

---

<p align="center">
  Made with ❤️ using IoT Technologies
</p>
