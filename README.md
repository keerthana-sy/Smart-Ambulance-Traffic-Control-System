# Smart-Ambulance-Traffic-Control-System
Smart Ambulance Traffic Signal Override System is an IoT-based intelligent traffic management solution designed to reduce ambulance response time during emergencies. The system enables an approaching ambulance to communicate with nearby traffic signals using wireless communication and automatically provides a green signal along its route. 
# 🚑 Smart Ambulance Traffic Signal Override System

An IoT-based intelligent traffic management system that provides priority to ambulances by automatically controlling traffic signals. The system detects an approaching ambulance, changes the traffic signal to green in its direction, sends ambulance details to the hospital, and logs all events for monitoring and analysis.

---

## 📌 Project Overview

Traffic congestion is one of the major causes of delayed emergency medical services. This project aims to reduce ambulance response time by creating an automated traffic signal override system using IoT technologies.

The ambulance unit continuously monitors its location and emergency status. When the siren is activated, it transmits the ambulance's location and patient information to nearby traffic signal controllers and hospitals. The traffic controller immediately switches the signal to green, allowing the ambulance to pass safely. Once the ambulance crosses the junction, the traffic signal resumes its normal operation.

---

## ✨ Features

- 🚑 Automatic ambulance detection
- 🚦 Intelligent traffic signal override
- 📍 Real-time GPS location tracking
- 📡 Long-range wireless communication (LoRa)
- 🏥 Hospital notification system
- 🔔 Emergency buzzer alerts
- ☁️ Cloud database logging
- 📊 Event monitoring and analysis
- 💰 Low-cost IoT implementation

---

## 🛠 Technologies Used

- ESP32
- Arduino IDE
- GPS Module (NEO-6M)
- LoRa Communication
- OLED Display
- Relay Module
- Firebase / MQTT
- Embedded C
- IoT

---

## 🔧 Hardware Components

- ESP32 Microcontroller
- GPS Module
- LoRa Transmitter & Receiver
- Siren Sensor
- Relay Module
- OLED Display
- LEDs
- Buzzer
- Power Supply
- Connecting Wires

---

## ⚙️ System Architecture

```
Ambulance Unit
      │
      │ GPS + Siren Detection
      ▼
LoRa Communication
      │
      ▼
Traffic Signal Controller
      │
      ├── Override Traffic Signal
      ├── Display Ambulance Information
      └── Send Data to Cloud

      │
      ▼
Hospital Unit
      │
      ├── Display Patient Information
      └── Activate Emergency Alert
```

---

## 🔄 Working

1. Ambulance activates the emergency siren.
2. GPS module collects the ambulance location.
3. ESP32 sends the location and patient details using LoRa.
4. Traffic signal controller receives the message.
5. The traffic signal changes to green for the ambulance.
6. Hospital receives patient information and generates an alert.
7. Event data is stored in the cloud database.
8. After the ambulance passes, the traffic signal returns to normal.

---

## 📊 Advantages

- Reduces ambulance waiting time
- Improves emergency response
- Enhances patient safety
- Low-cost implementation
- Easy to deploy
- Suitable for Smart City applications

---

## 🌍 Applications

- Smart Cities
- Emergency Medical Services
- Traffic Management
- Hospitals
- Disaster Management
- Public Safety Systems

---

## 📈 Future Enhancements

- AI-based traffic prediction
- Mobile application for live tracking
- Integration with Google Maps
- Multiple ambulance priority management
- 5G communication support
- Smart City integration

---

## 📂 Project Structure

```
Smart-Ambulance-Traffic-Signal-Override-System
│
├── README.md
├── code
│   ├── ambulance_unit.ino
│   ├── traffic_unit.ino
│   └── hospital_unit.ino
│
├── docs
│   └── Project_Report.pdf
│
├── ppt
│   └── Project_Presentation.pptx
│
├── images
│   ├── system_architecture.png
│   ├── hardware_setup.jpg
│   └── output.png
│
└── LICENSE
```

---

## 🎯 Objectives

- Reduce ambulance response time.
- Automate traffic signal management.
- Improve emergency healthcare services.
- Provide real-time communication between ambulances and hospitals.
- Maintain event logs for monitoring and analysis.

---

## 👩‍💻 Developed By

**Keerthana Jangili**

Bachelor of Engineering (Computer Science and Engineering)

Chaitanya Bharathi Institute of Technology (CBIT)

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
