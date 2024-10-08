# Object Detection Alarm

## Overview

The Object Detection Alarm system uses an ultrasonic sensor to detect objects within a specified distance. If an object is detected within the defined safety distance, a buzzer is activated along with an LED, signaling that the object is too close. This project is ideal for safety applications, robotics, or automation systems.

## Features

- Ultrasonic distance measurement to detect nearby objects
- Buzzer and LED alerts for object proximity
- Real-time distance monitoring via Serial Monitor
- Simple setup with Arduino

## Components Used

- Arduino (e.g., Arduino Uno)
- Ultrasonic Sensor (e.g., HC-SR04)
- Buzzer
- LED
- Resistor (for the LED, typically 220Ω)
- Breadboard and jumper wires

## Code Explanation

The code is written in C++ using the Arduino framework. It configures the ultrasonic sensor to measure the distance of nearby objects. If an object is detected within the safety distance (e.g., 8 cm), the buzzer and LED are turned on to signal the detection. The measured distance is also printed to the Serial Monitor for real-time monitoring.

