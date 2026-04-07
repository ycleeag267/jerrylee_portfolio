---
layout: page
title: Advanced CAV Control & XAI
description: Bridging the gap between high-performance "black-box" driving models and safety-critical interpretability.
img: assets/img/research_preview.jpg # Upload a graph or simulation screenshot here
importance: 2
category: research
---

My research at the UT Austin **Mobility Systems Lab** focuses on the intersection of dynamic systems, robust control theory, and Explainable AI (XAI). To make autonomous systems a reality, they must be highly responsive to physical hardware constraints and highly transparent to human users. 

Below are the three primary pillars of my current research.

### 1. Robust Control for Hardware Latency
Physical vehicles are not perfect mathematical models. Actuators have limits, and networks have latency. 
* **The Problem:** High-speed autonomous path-tracking often fails when control inputs are delayed by physical steer-by-wire mechanics.
* **The Solution:** I developed a practical control method that actively compensates for time-delayed steering system dynamics. By modeling the delay into the control loop, the vehicle maintains stability and precision at high speeds. 
* **Publication:** *Practical Method for High-Speed Path-Tracking Control of Vehicles with Time-Delayed Steering System Dynamics* (Journal).

### 2. Explainable AI (XAI) in Driving Models
As autonomous systems rely more on deep learning, they become "black boxes," making it difficult to guarantee safety or understand failure modes.
* **The Problem:** Highly accurate driving models are often mathematically opaque.
* **The Solution:** I utilized Explainable Boosting Machines (EBMs) to create highly interpretable approximations of these black-box models. This approach maintains high data efficiency while allowing engineers to see exactly how individual features (e.g., speed, lane position) influence the model's driving decisions.
* **Publication:** *Data-Efficient Interpretable Approximation of Black-Box Driving Models via Explainable Boosting Machines* (Conference).

### 3. Human-Machine Interface (HMI) and Trust
A lane-keeping system is only successful if the human driver trusts it enough to use it, but understands it well enough to take over when necessary.
* **The Problem:** How should a vehicle visually communicate its lane-keeping status to a driver without causing cognitive overload?
* **The Solution:** I conducted a detailed study evaluating the human impact of visual detail in lane-keeping system communication, measuring how different feedback mechanisms affect driver response times and situational awareness.
* **Publication:** *Human Impact of Visual Detail in Vehicle Lane-Keeping System Communication* (Conference).