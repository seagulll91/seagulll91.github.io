---
layout: single
author_profile: true
title: "About Me"
permalink: /
---

I am a second-year master’s student at Xiamen University, advised by Prof. Shihui Guo. My research interests lie in embodied intelligence and human motion capture methods for wearable sensing systems.

## Publications

<div class="publication-list">
{% for post in site.publications reversed %}
  {% include publication-card.html post=post %}
{% endfor %}
</div>
