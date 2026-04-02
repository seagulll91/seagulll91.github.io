---
layout: single
author_profile: true
title: "About me"
permalink: /
---

I am a second-year master’s student at Xiamen University, advised by Prof. Shihui Guo. My research interests lie in embodied intelligence and human motion capture methods for wearable sensing systems.

## Publications

{% for post in site.publications reversed %}
### [{{ post.title }}]({{ post.redirecturl | default: post.url }})

{{ post.excerpt | markdownify }}

{% if post.paperurl %}[Download Paper]({{ post.paperurl }}){% endif %}

<br><br>
{% endfor %}
