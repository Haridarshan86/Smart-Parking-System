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
![Dashboard](images/dashboard.png)
```

### Hardware Setup

```md
![Hardware](images/hardware.jpg)
```

### ThingSpeak Visualization

```md
![ThingSpeak](images/thingspeak.png)
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
