---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second-year master's student at Xiamen University, advised by Prof. Shihui Guo. My research interests lie in embodied intelligence and human motion capture methods for wearable sensing systems.

## Publications

{% for post in site.publications reversed %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>

  {% if post.paperurl %}
    <a href="{{ post.paperurl }}">Download Paper</a>
  {% endif %}
  {% if post.bibtexurl %}
    | <a href="{{ post.bibtexurl }}">Download Bibtex</a>
  {% endif %}
  {% if post.slidesurl %}
    | <a href="{{ post.slidesurl }}">Download Slides</a>
  {% endif %}

  <br><br>
{% endfor %}
