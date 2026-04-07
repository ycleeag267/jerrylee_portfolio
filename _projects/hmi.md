---
layout: page
title: HMI & Driver Trust
description: The human impact of visual detail in autonomous system communication.
img: assets/img/eyetracker_view.png # Suggestion: A photo of a dashboard UI or user-testing setup
importance: 3
category: research
---

A lane-keeping system is only successful if the human driver trusts it enough to use it, but understands it well enough to take over when necessary. 

### The Research
How should a vehicle visually communicate its lane-keeping status to a driver without causing cognitive overload? 

I conducted a detailed study evaluating the human impact of visual detail in lane-keeping system communication. By measuring how different dashboard feedback mechanisms affect driver response times and situational awareness, this work provides a framework for designing safer, more human-centric Human-Machine Interfaces (HMI).

<div class="row mt-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/eyetracker_view.png" title="Eye-Tracker View" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hmi_dashboard.png" title="Dashboard UI" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Eye-tracking setup used to monitor driver attention. Right: The visual dashboard variations tested during the study.
</div>

### Key Findings
By comparing the visual detail levels, the data revealed critical thresholds where added UI information stopped being helpful and started causing cognitive overload, increasing the driver's reaction time to critical takeover requests.

<div class="row mt-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hmi_results_chart.png" title="Results Chart" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Data demonstrating the correlation between UI visual density and driver reaction times.
</div>

**Publication:** *Human Impact of Visual Detail in Vehicle Lane-Keeping System Communication* (Conference).