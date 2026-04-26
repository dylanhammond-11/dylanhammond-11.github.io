---
layout: post
title: Hand Signal Interpreting Glove
order: 1
description: "Wearable glove system that classifies 25 hand signals using flex sensors, an MPU6050 IMU, and an embedded 1D CNN deployed on an ESP32 for real-time wireless control."
skills:
  - ESP32
  - MPU6050
  - Flex Sensors
  - Signal Processing
  - Sensor Fusion
  - CNN
  - Arduino IDE
main-image: /glovemain.jpg
---

The **Hand Signal Interpreting Glove** was developed as part of a senior capstone design project in collaboration with a team of five students. The goal of the system was to enable reliable, discreet communication through hand signals by translating physical gestures into wireless commands.

The glove uses five flex deflection sensors and an MPU6050 inertial measurement unit (IMU) to capture finger position and hand motion data. These signals are processed and classified using a one-dimensional convolutional neural network (1D CNN) deployed directly on an ESP32 microcontroller for real-time embedded inference.

The system achieved approximately **95% classification accuracy** across 25 distinct hand signals. Once a gesture is recognized, the glove wirelessly transmits the corresponding command to control a remote vehicle.

Additional system features include:

- Real-time gesture classification on embedded hardware  
- Wireless communication between glove and vehicle  
- Transmission mode toggle switches for system control  
- LED indicator lights for user feedback  
- Custom PCB design for compact and lightweight integration  


{% include image-gallery.html images="gloveopen.jpg, gloveclosed.jpg" height="400" %}

