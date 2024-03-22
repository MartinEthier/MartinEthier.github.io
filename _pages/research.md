---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I am a master's student at the [Waterloo Intelligent Systems Engineering Lab (WISE Lab)](https://uwaterloo.ca/waterloo-intelligent-systems-engineering-lab/), which is a research lab forcused on autonomous vehicles. My thesis research is focused on using neural rendering methods, such as Neural Radiance Fields (NeRFs) and 3D Gaussian Splatting, for autonomous vehicle simulation. These methods have the potential to allow the construction of perfectly photorealistic simulations, which could in theory eliminate one aspect of the sim2real gap. I am specifically interested in the evaluation of these methods for the AV simulation use case, and how to improve their performance in this domain. Since my research is a work in progress, I will post more information on here once my thesis is finished. Until then, here are a few presentations I made for my lab group on the topic of neural rendering:

### NeRF ()

In this presentation, I introduce Neural Radiance Fields (NeRFs) and present many follow-up papers that fix

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRH8eJgUXxQcb1_5Dj6zQLXO4CqROKsQ2d2bDPJkya8I-IxjvkSzQLplwPzv-GtNKSwTGtzeCimOesW/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

### UniSim ()

This paper from Waabi implements many of the changes I highlighted in my previous presentation to allow a NSG-type formulation to work for self-driving data

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRr-3ymGNYJX5nlr1YyuSw8vp-ee0_41iAebsdR0cDPVQNVAAgBkwEtL6g1AgAvRsAid3jgUFaWbJTZ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

### 3D Gaussian Splatting ()

3D Gaussian Splatting is a fundamental shift in the neural

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSCL8HBNUk8OG9VWmUH0uWSUfG_RksQNoP8DoZu2ftct4-WHi74G2KL_Uc62yjpyE0BY0TJOvZEkeqM/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


<!-- {% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %} -->