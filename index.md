---
layout: page
---

Welcome to my personal website.
This is a work in progress and at the moment it is very bare bones!
I will add to this site whenever I have time or inspiration to do so.
Check out what I'm up to on these pages:

{% for page in site.pages %}
 {% if page.title %}
   * [{{page.title}}]({{page.url}})
 {% endif %}
{% endfor %}
