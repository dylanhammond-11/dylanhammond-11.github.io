---
layout: post
title: Autonomous Following RC Car
description: "Autonomous RC vehicle that follows a target using ultrasonic sensing and closed-loop PID control designed and simulated in MATLAB/Simulink."
skills:
  - MATLAB
  - Simulink
  - PID Control
  - Arduino
  - Ultrasonic Sensors
  - Closed-Loop Control
main-image: /rccarside.png
---

The **Autonomous Following RC Car** is a mobile robotics system designed to maintain a controlled distance from a moving target using real-time sensor feedback and closed-loop control.

The vehicle uses three ultrasonic sensors to measure distance and relative position to a target object. These measurements are processed by two PID controllers that regulate both steering and forward velocity to achieve stable and responsive following behavior.

The control architecture was first modeled and simulated in MATLAB/Simulink to validate system behavior before implementation on embedded hardware.

Key system features include:

- Real-time distance measurement using multiple ultrasonic sensors  
- Dual PID controllers for steering and velocity regulation  
- Closed-loop control system designed and validated in MATLAB/Simulink  
- Embedded implementation on Arduino microcontroller  
- Autonomous object-following behavior in dynamic environments  

{% include image-gallery.html images="car_cl_simulink.png, rccarside.png" height="400" %}

{% include youtube-video.html id="bkOKexwXcTg" autoplay="false" %}
