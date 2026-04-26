layout: post
title: Hand Signal Interpreting Glove
description: |
  This project involved designing a wearable glove capable of recognizing 25 predefined hand signals and wirelessly transmitting commands to control a remote vehicle. The system enables reliable communication when voice or line-of-sight interaction is limited.

  The glove integrates five flex sensors and an MPU6050 inertial measurement unit (IMU) to capture finger deflection and hand motion data at approximately 100 Hz. Sensor signals are filtered and processed before being passed to a 1D convolutional neural network (CNN) deployed on an ESP32 microcontroller for real-time gesture classification.

  The embedded model achieved approximately 95% classification accuracy while meeting real-time latency and memory constraints of the microcontroller platform.

  The system includes mode-selection toggle switches, LED status indicators, and a custom printed circuit board (PCB) to create a compact and field-deployable design.

  I collaborated with a team of five students on this senior capstone project, focusing on sensor integration, signal processing, and embedded system implementation.
skills: 
  - ESP32
  - MPU6050
  - Embedded Systems
  - Signal Processing
  - Sensor Fusion
  - 1D Convolutional Neural Networks
  - Real-Time Systems
  - Arduino IDE
main-image: /glovemain1.jpg

{% include image-gallery.html images="gloveopen.jpg, gloveclosed.jpg" height="400" %}
