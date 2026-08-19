---
layout: page
title: Cooperative Adaptive Cruise Control
description: Longitudinal vehicle control via direct GM CAN bus integration.
img: assets/img/CACC.gif # Suggestion: A photo of the vehicle on the track or a CAN bus data plot
importance: 2
category: work
---

<div class="row mt-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
            loading="eager"
            path="assets/img/CACC.gif"
            title="CACC test"
            class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>
<div class="caption">
    CACC simulation in the loop, hardware in the loop, vehicle in the loop test visualization.
</div>

As the Connected and Automated Vehicle (CAV) Team Lead for the EcoCAR project, I worked on the development and deployment of a Cooperative Adaptive Cruise Control (CACC) system. The system is capable of recieving V2V information via radio to make safety aware and energy conserving longitudinal maneuvers. 

### Key Contributions
* **Algorithm Development:** Worked closely with team members in developing MPC controller and V2V integration. 
* **System Deployment:** Managed the transition of CACC algorithms from MATLAB/Simulink into deployable code on actual vehicle integrated hardware with system safety states in mind.
* **System Testing:** Validated the control logic using SIL, HIL simulation before executing closed-loop vehicle control during physical track testing, ensuring strict safety and performance compliance.

### Team Members

This project was completed as part of the EcoCAR CAV subteam in collaboration with:

- Krish Dalela — MPC controller development and testing
- Patrick Flaherty — Algorithm development and simulation
- Chinualumogu Nwosu - Analysis and test plans