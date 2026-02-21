---
layout: page
title: "Personal Projects"
permalink: /projects/personal/
nav: "true"
---

Here I will write about my personal projects.
<ul>
{% for post in site.posts %}
  {% if post.tags contains "scientific" %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endif %}
{% endfor %}
</ul>

[Back to main]({{ site.url }}/)
