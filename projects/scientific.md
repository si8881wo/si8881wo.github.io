---
layout: page
title: "Scientific Projects"
permalink: /projects/scientific/
nav: "true"
---

Here I will write about my scientific interests and projects.
In the meantime you can find an [overview of my publications on Google Scholar](https://scholar.google.com/citations?user=RbRXWM4AAAAJ&hl=en).

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
