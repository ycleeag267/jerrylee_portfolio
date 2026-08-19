---
layout: page
title: Lane Keeping System 
description: Lateral control logic and trajectory tracking development.
img: assets/img/SMC Lane Keeping.gif # Suggestion: A MATLAB/Simulink simulation curve showing lane centering
importance: 3
category: work
---
<div class="row mt-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
            loading="eager"
            path="assets/img/SMC Lane Keeping.gif"
            title="LKA"
            class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>
<div class="caption">
    HIL test result of the vehicle lane keeping for double lane change.
</div>

I was involved in developing, deploying, and testing the lane keeping system for the Cadilac Lyriq. The system utilizes lane detections to maintain vehicle within lane by transmitting torques commands to the power steering module through CAN. A robust controller is implemented to deal with disturbance, delay, and uncertainty.

### Key Contributions
* **Control Algorithm Development:** Designed and tuned the lateral control logic responsible for maintaining vehicle lane-centering at varied speeds.
* **CAN Messaging Architecture:** Configured the communication protocols required to accurately format and transmit lateral control commands to the vehicle's steering module via the GM CAN bus.
* **Simulation & Testing:** Utilized software and Hardware-in-the-Loop (HIL) environments to rigorously validate the trajectory tracking algorithms against simulated physical delays and steering limits.

### Team Members

This project was completed as part of the EcoCAR CAV subteam in collaboration with:

- Jonathan Simon — Robust algorithm development, simulation, and testing
- Praneel Seth — Algorithm development and simulation
- Kaitlyn Chen — Algorithm development and simulation