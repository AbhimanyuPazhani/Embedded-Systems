# Embedded Systems Tasks – Internship Work

## Overview
This repository contains embedded systems tasks completed during my internship at Hexwave Technologies as part of my final year training.

The work focuses on basic embedded programming, sensor interfacing, and hardware control using microcontrollers.

---

## Contents

### 1. IoT Temperature and Humidity Monitoring (ESP32 + ThingSpeak)

This program reads temperature and humidity data from a DHT22 sensor and uploads the data to the ThingSpeak cloud platform using Wi-Fi.

#### Features
- Wi-Fi connectivity using ESP32  
- Real-time temperature and humidity monitoring  
- Cloud data upload using ThingSpeak API  
- Periodic data update  

#### Components Used
- ESP32  
- DHT22 Sensor  
- ThingSpeak Cloud Platform  

#### Working
- The ESP32 connects to a Wi-Fi network  
- Reads temperature and humidity from the DHT22 sensor  
- Sends data to ThingSpeak at regular intervals  
- Displays status via Serial Monitor  

---

### 2. 7-Segment Display Counter using Shift Register

This program displays numbers from 0 to 99 on a 7-segment display using shift register communication.

#### Features
- Displays two-digit numbers (00–99)  
- Uses shift register to control display  
- Efficient pin usage  

#### Components Used
- Microcontroller (Arduino)  
- Shift Register  
- 7-Segment Display  

#### Working
- Numbers are split into tens and units  
- Each digit is mapped to its corresponding segment pattern  
- Data is sent serially using shiftOut()  
- Display updates every 300 ms  

---

## Skills Demonstrated
- Embedded C programming  
- Sensor interfacing  
- Serial communication  
- Basic IoT integration  
- Hardware control using GPIO  
- Debugging using Serial Monitor  

---

## Note
These are task-based implementations completed during internship training and are intended to demonstrate fundamental embedded systems concepts.

---

## Author
Abhimanyu P  
Tamil Nadu, India  
