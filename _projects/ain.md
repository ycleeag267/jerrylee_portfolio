---
layout: page
title: Automated Intersection Navigation (AIN)
description: Energy-optimized intersection transit utilizing V2X SPaT messaging.
img: assets/img/AIN.jpg # Suggestion: A diagram showing a vehicle approaching a traffic light with coast/stop logic
importance: 1
category: work
---
<div class="row mt-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
            loading="eager"
            path="assets/img/AIN fsm.jpg"
            title="AIN FSM"
            class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>
<div class="caption">
    State transition diagram for AIN algorithm.
</div>

In urban driving environments, intersections are a major source of energy waste due to hard braking and acceleration. As part of the UT Austin EcoCAR team, I was involved in developing the **Automated Intersection Navigation (AIN)** system designed to safely pass a singalized intersection.

### Key Contributions
* **V2X Integration:** Utilized Vehicle-to-Everything (V2X) communication with Cohda Wireless MK5 radio to ingest real-time Signal Phase and Timing (SPaT) messages from upcoming traffic lights.
* **Energy Optimization Logic:** Developed predictive algorithms to analyze the SPaT data and determine the most energy-efficient vehicle behavior: whether to maintain speed to clear the intersection, coast to a gradual halt, or stop completely.
* **System Integration:** Bridged the gap between infrastructure communication and the vehicle's longitudinal control systems to execute these energy-saving maneuvers smoothly.


### Team Members

This project was completed as part of the EcoCAR CAV subteam in collaboration with:

- Patrick Flaherty — Algorithm development and simulation
- Soumil Sarambale — Algorithm development and test plan