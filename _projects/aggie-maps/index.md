---
layout: post
title: Aggie Maps
description: |
 I developed a python-based path planning tool for pedestrian navigation on Utah State University campus. 
 The planner is user interactive and allows the user to select starting and ending locations via a GUI.

 The planner uses the A* algorithm to find the optimal path. A custom cost function is used to find the optimal
 path based on the current temperature. AT cold temperatures the planner prioritizes indoor path shortcuts to 
 keep the pedestrian warm. At warmer temperatures the planner prioritizes outdoor paths. 

 
skills: 
- Python
main-image: /aggiemaps_main.jpg

---
---

{% include image-gallery.html images="aggiemaps_2.jpg" height="400" %}
