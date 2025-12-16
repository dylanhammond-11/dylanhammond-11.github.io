---
layout: post
title: Aggie Maps
description: |
  AggieMaps is a python-based interactive path planner tool designed for optimal pedestrian routing around Utah State University campus. This tool uses the Dijkstra and A* search algorithms to find optimal routes using a topological representation of the USU campus.

  The main feature of AggieMaps is its environment-dependent cost-weighting. At low temperatures, indoor based paths are prioritized as pedestrians prefer to walk in closed warm spaces (despite sometimes being a slightly longer route). At warmer temperatures, the shortest distance outdoor path is prioritized. The outdoor temperature is a user input at the beginning of the simulation.
 
  The user interaction occurs through a simple graphical interface featuring a satellite image of the campus map. The user clicks on the interface to select the starting and ending node, and the simulation runs and the optimal route based on the conditions is found.

  For more information about this project and code please contact me as the repository is currently private.

 

 
skills: 
- Python
main-image: /aggiemaps_3.png

---
---

{% include image-gallery.html images="aggiemaps_2.png, aggiemaps_3.png, aggiemaps_main.png " height="400" %}
