---
layout: default
title: Monte Carlo
permalink: /montecarlo/
---

{% for item in site.montecarlo %}
  {% if item.title != 'Monte Carlo' %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ site.baseurl }}{{ item.link }}"></a></p>
  {% endif %}
{% endfor %}

