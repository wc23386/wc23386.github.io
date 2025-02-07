---
layout: page
title: Multilayered Network ML Analysis of News Credibility and Community Vulnerability to Misinformation
description: with background image
img: assets/img/projects/[P1 background] social_network.webp
importance: 1
category: work
related_publications: true
---

# Multilayered Network ML Analysis of News Credibility and Community Vulnerability to Misinformation
📅 Project Duration: September 2024 – December 2024
This project explores how online communities engage with political misinformation, using Reddit as a case study. By constructing a multilayered network of news sources based on credibility and analyzing user interactions, the study identifies communities most susceptible to low-credibility or biased content.
## Key Methods:
1. LLM-Based Credibility Scoring & Bias Analysis: Implementing a language model architecture to assign credibility scores across nine news sources, positioning communities within a credibility-bias space to track their media exposure and engagement trends.
2. User Embedding & Community Detection: Mapping user groups based on relationships between posts and news sources.
3. ACE Scoring for Anomaly Detection: Identifying behavioral anomalies in heterogeneous networks to highlight communities at higher risk.

The project’s main contribution lies in understanding how media exposure influences community susceptibility over time, offering insights into misinformation spread and potential mitigation strategies. [P1 poster](assets/img/projects/[P1 poster] Community_Susceptibility_Detection_to_Misinformation.pdf) [P1 paper](assets/img/projects/[P1 paper] Community_Susceptibility_Detection_to_Misinformation.pdf)

<!-- <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
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

{% endraw %} -->
