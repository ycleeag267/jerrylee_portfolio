---
layout: page
title: Explainable AI in Driving Models
description: Approximating black-box models for safety-critical interpretability.
img: assets/img/EBM.jpg # Suggestion: A feature importance chart or Partial Dependence Plot
importance: 2
category: research
---
<div class="row mt-4 mb-4">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
            loading="eager"
            path="assets/img/EBM.jpg"
            title="EBM"
            class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>
<div class="caption">
    Interpretable contribution of feature on decision making (to stop).
</div>
Most SOTA (state of the art) autonomous driving systems rely more heavily on deep learning, and due to this, they are mathematical "black boxes." While high performing, this lack of transparency makes it incredibly difficult to guarantee safety or understand failure modes in real-world deployment.

### The Research
I researched methods to make these systems mathematically transparent without sacrificing their capability. 

By utilizing **Explainable Boosting Machines (EBMs)**, I created highly interpretable approximations of black-box driving models. This approach maintains high data efficiency while allowing engineers to see exactly how individual features (e.g., speed, lane position) influence the model's driving decisions.
