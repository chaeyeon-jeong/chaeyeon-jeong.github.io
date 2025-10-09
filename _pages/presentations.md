---
title: "Presentations"
permalink: /presentations/
layout: archive
author_profile: true
---

I have given talks and presentations at academic conferences and symposia,
mainly focusing on digital humanities, classical Korean literature,
and narrative visualization. Below is a list of selected presentations.

{% include base_path %}

{% for post in site.presentations reversed %}
  {% include archive-single.html %}
{% endfor %}
