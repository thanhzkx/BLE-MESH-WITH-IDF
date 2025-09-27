# 🔗 BLE Mesh Monitoring System

> **Description**: Machine monitoring system using **ESP32 and BLE Mesh**.  
> Demonstrates provisioning, sensor data transmission, and relay operation for stable communication in industrial environments.

---

## 📌 Introduction
This project was developed during an internship at **Duy Anh System Management Solutions**.  
It shows how **Bluetooth Low Energy (BLE) Mesh** can be used to monitor machines, transmit sensor data, and maintain stable communication even when nodes are out of direct range.



## 📊 Results & Evaluation
- Sensor data successfully transmitted from **Sensor Server → Sensor Client**.  
- Relay ensured stable communication when Client was out of direct range.  
- Logs confirmed proper decoding of messages (Sensor Status, Descriptor, Cadence, etc.).  



---

## ⚙️ Components
- ESP32-C3 Super Mini  
- DHT11 / DHT22 (temperature & humidity sensor)  
- Power supply (5V adapter or battery)  
- USB-TTL for programming  
- Supporting passive components  

---

## 📂 Repository Contents
- Firmware for **Sensor Server** and **Sensor Client** nodes.  
- Gateway code for forwarding data to server/cloud.  
- Reference diagrams, schematics, and test logs.  

---

## 🚀 Future Work
- Extend system with **additional sensors** (current, voltage, power) for machine monitoring.  
- Apply in **smart agriculture** with IoT + AI (e.g., monitoring temperature/humidity in greenhouses).  
- Develop **mobile/web dashboard** for real-time data visualization.  

---

## 👨‍💻 Author
Nguyễn Minh Thành – Ho Chi Minh City University of Technology (HCMUT)  
✉️ Contact: **nguyenminhthanh.office@gmail.com**


