---
layout: default
title: Home
permalink: https://anazli.github.io/randomThoughts
---

# Categories

{% include categories.html %}

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


