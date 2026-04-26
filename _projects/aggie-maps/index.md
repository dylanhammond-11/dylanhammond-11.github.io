---
layout: post
title: Aggie Maps
order: 4
description: "Python-based path planning tool that computes optimal pedestrian routes using Dijkstra and A* search algorithms with environment-dependent cost weighting."
skills:
  - Python
  - A* Search
  - Dijkstra Algorithm
  - Graph Algorithms
  - Path Planning
  - GUI Development
main-image: /aggiemaps_main.png
---

**Aggie Maps** is an interactive path planning tool developed to compute optimal pedestrian routes across the Utah State University campus using graph-based search algorithms.

The campus environment is modeled as a topological graph where nodes represent key locations and edges represent traversable paths. Dijkstra and A* search algorithms are used to compute optimal routes between user-selected start and destination points.

A key feature of the system is **environment-dependent cost weighting**. The path planner dynamically adjusts edge costs based on outdoor temperature conditions:

- At low temperatures, indoor routes are prioritized to reflect user comfort and environmental constraints  
- At warmer temperatures, the shortest outdoor path is preferred  
- Temperature is provided as a user input at runtime  

User interaction occurs through a graphical interface displaying a satellite map of the campus. The user selects start and destination nodes by clicking on the map, and the system computes and visualizes the optimal route based on current conditions.

Key system features include:

- Graph-based modeling of campus navigation network  
- Implementation of Dijkstra and A* search algorithms  
- Environment-dependent path cost weighting  
- Interactive graphical user interface for route selection  
- Real-time visualization of computed optimal paths  

For additional details or access to the source code, please contact me as the repository is currently private.

{% include image-gallery.html images="aggiemaps_2.png, aggiemaps_3.png, aggiemaps_main.png" height="400" %}
