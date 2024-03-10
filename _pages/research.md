---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current graduate research is focused on neural rendering methods, such as Neural Radiance Fields (NeRFs) and 3D Gaussian Splatting, applied to autonomous vehicle simulation. I am specifically interested in the evaluation of these methods for the AV simulation use case, and how to improve their performance in this domain.


{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}