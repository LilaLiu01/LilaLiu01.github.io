---
layout: page
title: Serial Dependence in Radiologists
description: with background image
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

Stimuli: 3 prototypes * 48 morph shapes between each pair = 147 stimuli\
Location: 3.7° shapes blurred by gaussian kernel size of 1.55°, presented at peripheral visual field with 4.4° eccentricity.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/13.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
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
</div>
<div class="caption">
    Even in trained radiologists, they exhibited a perceptual pull of ~ 13% towards previously seen tumors.
</div>

You can also put regular text between your rows of images, even citations {% cite fischer2014serial %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
