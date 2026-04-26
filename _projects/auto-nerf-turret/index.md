---
layout: post
title: Automated Tracking Turret
order: 2
description: "Autonomous 3D-printed turret that uses computer vision and PID control to track and engage moving targets using real-time servo actuation."
skills:
  - Python
  - OpenCV
  - Arduino
  - PID Control
  - Computer Vision
  - SolidWorks
main-image: /TurretMain.jpg
---

The **Automated Tracking Turret** is a fully autonomous system designed and built from scratch to detect, track, and engage moving targets using computer vision and closed-loop control.

The turret uses a USB camera paired with OpenCV to detect and track objects in real time. Target position is converted into control error signals, which are processed by PID controllers to generate smooth and accurate pan and tilt commands.

An Arduino Uno microcontroller executes the control logic and drives the actuators. The mechanical structure was fully designed in SolidWorks and fabricated using 3D printing.

The system includes:

- Real-time object detection and tracking using OpenCV  
- Closed-loop PID control for stable pan and tilt motion  
- Three MG90S servo motors for pan, tilt, and loading control  
- Dual DC motors driving a wheel-based projectile launcher  
- Fully custom 3D-printed mechanical design and assembly  

{% include image-gallery.html images="TurretRight.jpg, TurretLeft.jpg, TurretTop.jpg, TurretFront.jpg" height="400" %}
