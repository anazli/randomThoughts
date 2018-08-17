---
layout: default
title: Home
permalink: /
---

# Categories

{% include categories.html %}

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="https://anazli.github.io/randomThoughts{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


