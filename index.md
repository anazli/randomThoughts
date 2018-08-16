---
layout: default
title: Home
permalink: /
---

<meta name="viewport" content="width=device-width, initial-scale=1" />

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


