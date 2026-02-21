---
layout: default
title: "Personal Projects"
permalink: /projects/personal/
nav: "true"
---

Here I will write about my personal projects.

# first try

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

# second try

{% for tag in site.tags %}
  ## {{ tag[0] }}
  {% for post in tag[1] %}
      [{{ post.title }}]({{ post.url }})
      {{ post.excerpt }}
      ---
  {% endfor %}
{% endfor %}

[Back to main]({{ site.url }}/)
