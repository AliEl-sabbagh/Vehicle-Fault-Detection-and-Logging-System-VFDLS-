# Vehicle Fault Detection and Logging System (VFDLS) 🚗🔧

## Overview

The Vehicle Fault Detection and Logging System (VFDLS) is an embedded systems project developed using the **Tiva-C Microcontroller**.
The system is designed to monitor different vehicle conditions in real time, detect faults, log errors into EEPROM memory, and display system status through LCD, UART terminal, and 7-segment displays.

---

## Features

### 🚘 Ultrasonic Parking Sensor

* Detects nearby obstacles.
* Logs a fault when the measured distance becomes dangerously close.

### 🌡️ Temperature Monitoring using DHT11

* Monitors surrounding temperature in real time.
* Logs an error when temperature exceeds a predefined threshold.

### 💧 Water Level Detection System

* Detects the water level inside the car.
* Logs an error when the water level drops below the threshold.

### 🔥 Smoke Detection System

* Detects smoke levels inside the engine compartment.
* Generates a fault alert when smoke concentration exceeds the safe threshold.

### 🌙 Automatic Light Detection using LDR

* Detects low ambient light conditions.
* Logs a warning when darkness is detected.

### ⏰ RTC + 7-Segment Display

* Displays real-time clock data.
* Stores the exact timestamp for every logged fault.

### 💾 EEPROM Fault Logging

* Stores all detected faults permanently in internal EEPROM memory.
* Allows retrieval of stored faults through UART communication.

### 🖥️ LCD & UART Interface

* Displays real-time system status and fault messages.
* UART terminal used for monitoring and retrieving logged faults.

---

## Technologies Used

* Embedded C
* Tiva-C Microcontroller
* UART Communication
* EEPROM Memory
* GPIO Interfacing
* Sensor Interfacing
* RTC Module
* LCD Display
* 7-Segment Display

---

## Hardware Components

* Tiva-C LaunchPad
* DHT11 Sensor
* Ultrasonic Sensor
* Water Level Sensor
* Smoke Sensor
* LDR Sensor
* RTC Module
* LCD 16x2
* 7-Segment Display
* EEPROM (Internal)

---

## System Capabilities

* Real-time monitoring
* Fault detection and logging
* Timestamped error reporting
* EEPROM data storage
* UART communication with PC terminal

---

## Team Members

* Ali Ahmed
* Mohammed Emad
* Saif Hany
* Marwan Hassan
* Tasnim Ahmed


