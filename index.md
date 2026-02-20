---
layout: default
permalink: /index/
---

Welcome to my personal website.

[About me](about/me)

[CV](about/cv)

[Personal projects](projects/personal)

[Scientific projects](projects/scientific)

[Link to a test page](test)

Here you can find my public git repos:
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
