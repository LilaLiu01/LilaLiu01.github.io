---
layout: page
title: Serial Dependence in Radiologists
description: Serial dependence affects radiologists' recognition of lesions in radiographs, with perception on average trials being influenced by the most recent ones.
img: assets/img/4.jpg
importance: 1
category: Research Projects
related_publications: true
---


Human perception is influenced by prior visual experiences, with the tendency of our visual system to misinterpret current stimuli in the direction of previously encountered stimuli being referred to as serial dependence {% cite fischer2014serial %}.

The visual environment exhibits temporal auto-correlation. \
Some important tuning properties of serial dependencies:

    ---
    Temporal tuning: SD effect was also found to decrease linearly with increasing temporal delay between current and previous trials

    Spatial tuning: SD effect diminishes progressively as the spatial distance between current and previous objects increases.

    Feature tuning: SD is observed with more similar sequential objects and is evident in low-level features such as orientation, position, color, and shape.

    Attentional tuning: Attention can influence the decay of SD over time, as well as in terms of spatial and feature similarity.
    ---

**Stimuli:** 3 prototypes * 48 morph shapes between each pair = 147 stimuli\
**Location:** 3.7° shapes blurred by gaussian kernel size of 1.55°, presented at peripheral visual field with 4.4° eccentricity.

<div class="row">
    <div class="col-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/13.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/14.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Stimuli set and the lesion appeared in the adjustment task (continuous report).
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/15.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/17.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Even in trained radiologists, they exhibited a perceptual pull of ~ 13% towards previously seen tumors.
</div>

- Temporal tuning analysis:\
The von Mises function is a circular probability distribution, while the derivative of the von Mises fit can help model how the circular variable (shapes) evolves over response errors.

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Temporal tuning is measured by fitting a derivative of the von Mises function to each subject's data. 
</div>

- Spatial tuning analysis: 

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/16.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Relative angular distance was divided into 3 groups between 0°–180°. 
</div>

I'm interested in mitigating the negative impact of serial effects to enhance diagnostic accuracy.
