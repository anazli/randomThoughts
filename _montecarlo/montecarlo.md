---
layout: default
title: Monte Carlo
permalink: /randomThoughts/montecarlo/
---
{% for item in site.montecarlo %}
  {% if item.title != 'Monte Carlo' %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
  {% endif %}
{% endfor %}

