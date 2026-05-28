# ESP32 Smart Home Automation System

An IoT-based smart home automation system built using ESP32, Arduino IoT Cloud, IR remote control, manual switches, and DHT11 environmental sensing.

The system enables real-time appliance control through:
- Arduino IoT Cloud dashboard
- IR remote
- Physical wall switches

It also provides live temperature monitoring and WiFi connection feedback.

---

## Features

- Control 4 appliances remotely using Arduino IoT Cloud
- Manual switch override support
- IR remote-based wireless control
- Real-time temperature monitoring using DHT11
- WiFi connection status indication
- Real-time cloud synchronization
- Multi-control redundancy system
- Low-cost and scalable IoT architecture

---

## Hardware Used

| Component | Quantity |
|---|---|
| ESP32 Dev Board | 1 |
| 4-Channel Relay Module | 1 |
| DHT11 Sensor | 1 |
| IR Receiver Module | 1 |
| IR Remote | 1 |
| Push Buttons / Switches | 4 |
| LEDs | 1 |
| Jumper Wires | Multiple |

---
## System Architecture
<img width="1536" height="1024" alt="architecture" src="https://github.com/user-attachments/assets/d63fe284-d6c5-400a-a918-c4ac434f8e1a" />

## Pin Configuration
---
| Component | ESP32 Pin |
|---|---|
| Relay 1 | GPIO 23 |
| Relay 2 | GPIO 19 |
| Relay 3 | GPIO 18 |
| Relay 4 | GPIO 5 |
| Switch 1 | GPIO 13 |
| Switch 2 | GPIO 12 |
| Switch 3 | GPIO 14 |
| Switch 4 | GPIO 27 |
| DHT11 | GPIO 4 |
| IR Receiver | GPIO 35 |
| WiFi LED | GPIO 2 |


<img width="1536" height="1024" alt="ChatGPT Image May 28, 2026, 07_02_21 PM" src="https://github.com/user-attachments/assets/eb710553-7390-436a-9c09-5b583d9e2727" />

---

## Software & Libraries

- Arduino IDE
- Arduino IoT Cloud
- ArduinoIoTCloud Library
- IRremote Library
- DHT Sensor Library

---

## Working Principle

The ESP32 connects to WiFi and synchronizes appliance states with Arduino IoT Cloud. Appliances can be controlled using:
1. Cloud dashboard
2. IR remote
3. Manual switches

The DHT11 sensor continuously sends temperature data to the cloud dashboard.

---

## Applications

- Smart Home Automation
- IoT-based Appliance Control
- Remote Monitoring Systems
- Energy Management Systems

---

## Future Improvements

- Voice assistant integration
- MQTT protocol support
- Energy monitoring
- Mobile application development
- Scheduling & automation rules

---

## Author

Ujjwal Kumar
Electronics & Communication Engineering
Indian Institute of Information Technology Senapati
