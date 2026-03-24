# 🌡️ Arduino Smart Thermal Regulation System

This is Arduino-based smart thermal regulation system prototyped and simulated in **Tinkercad**. The project focuses on real-time temperature monitoring and automated response mechanisms to maintain specific environmental conditions.

## 🚀 Project Overview
The system acts as an intelligent thermostat. It continuously samples ambient temperature, displays real-time data on an LCD/Serial monitor, and triggers an automated response (like a cooling fan or heating element) when pre-defined thresholds are breached.

## 🛠️ Tech Stack
* **Platform:** Tinkercad (Virtual Prototyping)
* **Microcontroller:** Arduino Uno R3
* **Programming Language:** C++ (Arduino Wiring)
* **Key Components:** * TMP36 Temperature Sensor
    * LCD 16x2 Display (I2C/Parallel)
    * DC Motor (Simulated Fan)
    * RTC Module (for Clock functionality)
    * Potentiometers & LEDs for feedback

## 🧩 Key Features
* **Sensor-Driven Control:** Uses precise analog-to-digital conversion to interpret temperature data.
* **Real-Time Feedback:** Displays both current time and temperature simultaneously.
* **Automated Regulation:** Implements hysteresis logic to prevent "chattering" (frequent on/off switching) of the actuator.
* **Prototyping Ready:** Circuit design is fully tested in a simulation environment and ready for PCB implementation.

## 🖼️ Gallery

 Circuit Design (Tinkercad) 
| :---: | 
 ![IMG](Thermo_clock/ThermoClock.png) 

> **Live Simulation:** [View and Run on Tinkercad](https://www.tinkercad.com/things/jICS4unwTMm-thermo-clock-?sharecode=2dXkuUk0Ebovbbu9fkB9iWQa-_l2R4tBc6zC2da8r9Q)

