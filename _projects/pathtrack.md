---
layout: page
title: High-Speed Path-Tracking Control
description: Compensating for time-delayed steering system dynamics in physical vehicles.
img: assets/img/pathtracking.gif # Suggestion: A MATLAB/Simulink graph showing tracking error reduction
importance: 1
category: research
---

Physical vehicles are not perfect mathematical models. Actuators have limits, and networks have latency. High-speed autonomous path-tracking often fails when control inputs are delayed by physical steer-by-wire mechanics.
<div class="row mt-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pathtracking.gif" title="Path Tracking Simulation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Simulation demonstrating active compensation for steering system delays during high-speed maneuvers.
</div>
### The Research
I developed a practical, robust control method that actively compensates for time-delayed steering system dynamics. 

By mathematically modeling the physical delay directly into the control loop, the system can anticipate the vehicle's state, allowing it to maintain dynamic stability and precision path-tracking even at high speeds.

**Publication:** *Practical Method for High-Speed Path-Tracking Control of Vehicles with Time-Delayed Steering System Dynamics* (Journal).