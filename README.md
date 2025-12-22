# 🔥 Fire Fighting System Using Microcontroller (ATmega32)

> **An embedded systems project for early fire detection, alerting, and automated response using sensors, GSM communication, and microcontroller control logic.**

---

## 📌 Project Overview

Fire accidents are a major threat to human life and property, especially in environments lacking fast and reliable fire protection systems.
This project presents the **design and implementation of an automatic fire fighting system** using the **ATmega32 microcontroller**.

The system continuously monitors environmental conditions such as **temperature and fire indicators**, detects abnormal situations, alerts users locally and remotely, and can initiate **fire extinguishing actions** automatically or manually.

---

## 🎯 Objectives

* Design a **cost-effective and standalone fire fighting system**
* Detect fire hazards using **temperature sensors**
* Provide **visual, audible, and SMS alerts**
* Support **automatic and manual operation modes**
* Simulate and test the system using **Proteus**
* Implement the system using real hardware components

---

## 🧠 System Features

* 🔥 **Fire & heat detection** using LM35 temperature sensors
* 📟 **Real-time monitoring** via 16×2 LCD display
* 🔊 **Audible alarm** using buzzer
* 📩 **SMS notifications** via GSM module (SIM900)
* 🧩 **Zone-based monitoring** for multiple areas
* ⚙️ **Automatic & manual control modes**
* 💡 **LED indicators** for fault and alarm status
* 🧪 **Proteus simulation** before hardware deployment

---

## 🏗️ System Architecture

**Main Components:**

* **Microcontroller:** ATmega32
* **Sensors:** LM35 temperature sensors
* **Communication:** SIM900 GSM module
* **Display:** 16×2 LCD
* **Driver:** ULN2003 motor driver
* **Alerts:** Buzzer & LEDs
* **Input:** Push buttons
* **Software Tools:**

  * BASCOM-AVR (Embedded C/BASIC)
  * Proteus (Simulation)

---

## 🔌 Hardware Block Diagram

```
[ Sensors ] ──▶ [ ATmega32 ] ──▶ [ LCD Display ]
                   │
                   ├──▶ [ GSM Module (SMS) ]
                   ├──▶ [ Buzzer ]
                   ├──▶ [ LEDs ]
                   └──▶ [ Actuators / Relays ]
```

---

## 💻 Software Description

* The microcontroller continuously reads sensor data via ADC
* Threshold comparison determines **normal, warning, or fire states**
* On fire detection:

  * Alarm is activated
  * LCD displays threat type
  * SMS is sent to the user
  * Fire extinguishing unit can be triggered
* System supports **interrupts and real-time operation**
* Code written using **BASCOM-AVR**

---

## 📡 GSM Alert System

* Uses **SIM900 GSM module**
* Sends **SMS notifications** on:

  * Fire detection
  * Sensor faults
  * Zone activation
* Enables **remote monitoring** of buildings

---

## 🧪 Simulation & Testing

* Full system simulated using **Proteus**
* Verified:

  * Sensor response accuracy
  * Alarm triggering
  * GSM communication
  * LCD output
* Hardware testing confirmed stable real-time performance


## 📁 Repository Structure (Recommended)

```
Fire-Fighting-System/
│
├── code/
│   └── 
│
├── simulation/
│   └──
│
├── hardware/
│   └── 
│
├── report/
│   └── 
│
└── README.md
```

---

## 👨‍💻 Project Team

* **Abram Maged** – 20190003
* **Moustafa Ahmed** – 20211003
* **Hossam Hamdy** – 20210369
* **Mohamed Awes** – 20210696
* **Hassan Alaa El-Dein** – 20200571

---

## 🚀 Future Improvements

* Add **smoke & flame sensors**
* Mobile application for alerts
* IoT dashboard (Wi-Fi / MQTT)
* Camera-based fire detection
* Cloud-based monitoring

---



