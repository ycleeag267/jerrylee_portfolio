---
layout: page
title: Cooperative Adaptive Cruise Control
description: Longitudinal vehicle control via direct GM CAN bus integration.
img: assets/img/cacc_preview.jpg # Suggestion: A photo of the vehicle on the track or a CAN bus data plot
importance: 2
category: work
---

As the Connected and Automated Vehicle (CAV) Team Lead for the EcoCAR project, I managed the development and deployment of a Cooperative Adaptive Cruise Control (CACC) system, bypassing middleware like ROS to communicate directly with the vehicle's native architecture.

### Key Contributions
* **Direct CAN Communication:** Engineered the system to interface directly with the GM CAN bus, reading native vehicle states and writing longitudinal torque/braking commands without relying on ROS.
* **Control Translation:** Managed the transition of advanced longitudinal control algorithms from MATLAB/Simulink into deployable code.
* **Hardware-in-the-Loop (HIL):** Validated the control logic using extensive HIL simulation before executing closed-loop vehicle control during physical track testing, ensuring strict safety and performance compliance.