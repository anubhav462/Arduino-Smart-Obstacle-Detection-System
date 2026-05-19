# Arduino Smart Obstacle Detector

An Arduino-based obstacle detection system using the FC-51 IR sensor module for detecting nearby objects and providing real-time indication.

---

## Project Overview

The Arduino Smart Obstacle Detector is a simple embedded systems project designed to detect nearby objects using an infrared obstacle sensor module. The system continuously monitors the surroundings and activates visual indication when an obstacle is detected.

This project is useful for beginners learning:
- Arduino programming
- Sensor interfacing
- Embedded systems basics
- Automation concepts

---

## Components Used

- Arduino UNO
- FC-51 IR Obstacle Sensor
- LED
- Resistor
- Breadboard
- Jumper Wires

---

## Project Files

| File Name | Description |
|---|---|
| `arduino_smart_obstacle_detector.ino` | Main Arduino source code |
| `sensor_testing_log` | Sensor testing and observation file |
| `obstacle_detector_breadboard_build` | Breadboard setup/build file |
| `obstacle_detector_circuit_layout` | Circuit layout/design file |

---

## Working Principle

The FC-51 IR sensor emits infrared light continuously. When an object comes near the sensor, the reflected infrared light is detected by the receiver module.

The Arduino reads the sensor output signal and triggers LED indication whenever an obstacle is detected.

---

## Features

- Real-time obstacle detection
- Fast sensor response
- Simple hardware implementation
- Easy Arduino integration
- Beginner-friendly embedded project

---

## Applications

- Obstacle avoidance robots
- Smart automation systems
- Object detection systems
- Basic security systems
- Embedded systems learning

---

## Circuit Setup

The project includes breadboard setup and circuit layout files for hardware implementation.

---

## How to Run the Project

1. Connect the FC-51 sensor to Arduino UNO
2. Open `arduino_smart_obstacle_detector.ino` in Arduino IDE
3. Upload the code to Arduino UNO
4. Power the Arduino board
5. Place an object near the sensor
6. Observe LED indication on obstacle detection

---

## Future Improvements

- Add buzzer alert system
- Add OLED display
- Wireless monitoring using ESP32
- Mobile notification integration

---

## Technologies Used

- Arduino IDE
- Embedded C/C++
- IR Sensor Interfacing
- Basic Electronics

---

## Author

Anubhav Gupta
