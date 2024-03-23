---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I am currently a master's student at the [Waterloo Intelligent Systems Engineering Lab (WISE Lab)](https://uwaterloo.ca/waterloo-intelligent-systems-engineering-lab/), which is a research lab at the University of Waterloo focused on artificial intelligence for autonomous vehicles. My thesis research looks at using neural rendering methods, such as Neural Radiance Fields (NeRFs) and 3D Gaussian Splatting, for autonomous vehicle simulation. These methods have the potential to allow the construction of perfectly photorealistic simulations, which could in theory eliminate one aspect of the sim2real gap. I am specifically interested in the evaluation of these methods for the AV simulation use case, and how to improve their performance in this domain. Since my research is a work in progress, I will post more information on here once my thesis is finalized. Until then, here are a few talks I gave to my lab group on the topic of neural rendering.

## Building a Photorealistic Driving Simulator Using Neural Radiance Fields (April 3rd, 2023)

This is a talk I gave to the ECE 495 - Autonomous Driving class while I was the teaching assistant. In this talk, I introduce Neural Radiance Fields (NeRFs) and present many relevant papers that address the limitations of NeRFs. Then, I outline how one would combine these ideas to create a NeRF method that would be feasible as a simulation engine for autonomous vehicles.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRH8eJgUXxQcb1_5Dj6zQLXO4CqROKsQ2d2bDPJkya8I-IxjvkSzQLplwPzv-GtNKSwTGtzeCimOesW/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## UniSim: A Neural Closed-Loop Sensor Simulator (June 12th, 2023)

Here I present the UniSim paper from Waabi.ai, which implements many of the changes I highlighted in my previous presentation to allow an approach similar to Neural Scene Graphs, but works well on driving data and trains quickly. This paper also cleverly integrates LiDAR data into the pipeline, allowing the NeRF to make full use of the geometric constraints from the LiDAR data.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRr-3ymGNYJX5nlr1YyuSw8vp-ee0_41iAebsdR0cDPVQNVAAgBkwEtL6g1AgAvRsAid3jgUFaWbJTZ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## 3D Gaussian Splatting for Real-Time Radiance Field Rendering (October 2nd, 2023)

Here I present 3D Gaussian Splatting from researchers at Inria. This paper is a fundamental shift in the neural rendering space, switching from the slow sampling based ray-casting approach of NeRFs, to a technique that more closely resembles traditional rasterization. This allows 3D Gaussian Splatting to render scenes in real-time on consumer GPUs at essentially the same quality as the SOTA NeRF methods. As for autonomous vehicle simulation, using 3D Gaussian Splatting will reduce the cost of inference, at the cost of needing more storage space to save the trained gaussians.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSCL8HBNUk8OG9VWmUH0uWSUfG_RksQNoP8DoZu2ftct4-WHi74G2KL_Uc62yjpyE0BY0TJOvZEkeqM/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


<!-- {% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %} -->