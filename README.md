# Automated Fire Fighting Robot

## Table of Contents
- [Introduction](#introduction)
- [Required Components](#required-components)
- [Working Procedure](#working-procedure)
- [Screenshot](#screenshot)

## Introduction
The **Automated Fire Fighting Robot** is an Arduino UNO-based project designed to detect and extinguish fires. It can also detect obstacles in its path and navigate around them to reach the fire. The robot combines obstacle avoidance and fire detection to make sure that the fire is put out efficiently while avoiding barriers in its environment.

## Required Components
These following parts and tools are required for building this project:
- **Arduino UNO2560 R3**
- **Ultrasonic Sensor**
- **Fire Sensor**
- **Buzzer**
- **Servo Motor (SG90)**
- **L293D Motor Driver Module**
- **Mini DC Submersible Pump**
- **Small Breadboard with Power Supply**
- **6V DC Geared Motor 180RPM Dual Shaft**
- **4 Wheels**
- **Frame**
- **4WD Smart Robot Chassis Kit** (alternative of 9-11)
- **Wires and others**

## Working Procedure
### Obstacle Detection using Ultrasonic
The ultrasonic sensor communicates with the microcontroller through the TRIGGER and ECHO pins. When the microcontroller sends a positive pulse through the TRIGGER pin (at least 10 microseconds long), the sensor gets activated, and the ECHO pin will receive a HIGH pulse. The pulse width represents the distance between the sensor and the detected object.

### Obstacle Avoiding System
When the robot detects an obstruction within a 30-meter range, it pauses and uses the ultrasonic sensor to choose an obstruction-free path. The robot will then advance toward the cleared path.

### Fire Detection
The flame detector works by detecting the infrared radiation emitted by flames. When a fire is detected, the system triggers a response. The flame detector can respond faster and more accurately than smoke or heat detectors, providing real-time alerts to the robot.

### Fire Extinguishing
When fire is detected, the robot uses a mini DC submersible pump to spray water on the fire, extinguishing it instantly.

## Screenshot
- **Robot Image 1:** The front view of the robot.
![AFF1](https://github.com/SheikhAminul24/AutomatedFireFighter/assets/94759040/3c510aa9-1abf-4b62-af48-279bf3eb6bb8)

- **Robot Image 2:** The top view of the robot.
![AFF2](https://github.com/SheikhAminul24/AutomatedFireFighter/assets/94759040/70a88bd7-5de0-4c08-bec3-bd60f6939c3b)

