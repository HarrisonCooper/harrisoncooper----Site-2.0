---
layout: post
title: Dissertation - Development of an Agent-based Model Capturing Cellular Interactions Associated with Heart Attack
permalink: dissertation
image: /images/dissertation/dissertation.gif
tags: [ABM, Python, Testing]
---


Full paper can be viewed [here](https://drive.google.com/file/d/1gjQbezvDhW13MIbIzHyPbs36qkRHY4n9/view?usp=sharing).
Code can be found on GitHub [here](https://github.com/HarrisonCooper/dissertation).

# Background
* Endothelial cells migrate into wounds to heal blood vessel walls
![alt text](/images/dissertation/bloodvessel.png "Blood Vessel Wall")
* Over time cells turn Quiescent (G0) then Senescent
![alt text](images/dissertation/cellcycle.png "Endothelial Cell Cycle")
    * These cells act as barriers to migration
* As we age, the rate of healing is reduced
    * But by how much?
* Delayed healing leads to thrombosis

# Methods
* An Agent-based Model has been implemented in Python
    * Dynamic system of interacting cells
    * Allows individual representation of the three agents
    * Allows graphical output of behaviours
![alt text](/images/dissertation/confluence.png "Confluence showing 3 types of cells")
* Testing with unit tests, sensitivity analysis, and face validation

# Results
* Senescent cells act as barriers slowing migration
* Emergent behaviour of cells migrating into wound and proliferating cells turning Quiescent
* Largest change after 6.6% senescent ~ 41 years old
![alt text](images/dissertation/rateofhealing.png "Rate of healing at different ages")

# Conclusion
* As we age, wound healing rate decreases
    * Little change after 41 years of age
    * This increases the change of blood clot formation
* Further work:
    * Implement cell adhesion
    * Decrease time complexity
    * In vitro validation
