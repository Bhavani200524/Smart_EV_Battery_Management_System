# Smart_EV_Battery_Management_System
Smart EV Battery Management System with SOH prediction using IoT (Firebase) and Machine Learning.

## Overview
This project implements a smart Battery Management System (BMS) for Electric Vehicles using IoT and Machine Learning.

##  Features
- Real-time battery monitoring (Temperature, Voltage, Current)
- Firebase cloud integration
- Machine Learning-based SOH prediction
- Dashboard visualization
- Overheating protection system

##  System Architecture
- The proposed system follows a layered architecture integrating hardware, software, cloud, and machine learning components.
- The battery pack acts as the primary energy source, and its parameters are continuously monitored.
- Sensors are used to measure key parameters such as temperature, voltage, current, and battery charge level in real time.
- A microcontroller (ESP32) collects sensor data and performs initial processing and threshold checking.
- The system includes a temperature monitoring mechanism that compares real-time values with predefined safety limits.
- If the temperature exceeds the threshold, the system activates a cooling mechanism (fan) to prevent overheating.
- The microcontroller sends data to the Firebase cloud platform using Wi-Fi for real-time storage and remote access.
- The cloud database maintains both real-time and historical battery data for further analysis.
- A user dashboard/interface displays battery parameters such as battery percentage, temperature, voltage, and current.
- The system integrates a machine learning model that processes collected data to predict:
   - State of Health (SOH)
   - Remaining battery life
   - Driving range
   - Maintenance requirements
- The architecture supports real-time alerts and notifications for abnormal conditions such as overheating or high discharge rate.
- The system ensures continuous monitoring and feedback, enabling safe and efficient battery operation.
- The overall architecture is scalable and adaptable for real-world electric vehicle applications.

##  Hardware
- ESP32 / Arduino
- DHT11 Sensor
- LCD Display
- Relay & Cooling Fan

##  Software
- Firebase Realtime Database
- Machine Learning Model
- Dashboard UI

##  Output
- Battery Life Prediction
- Travel Range Estimation
- Maintenance Alerts


