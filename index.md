---
layout: page
---

Welcome to my personal website.



[About me](about/me)

[CV](about/cv)

[Personal projects](projects/personal)

[Scientific projects](projects/scientific)

[Link to a test page](test)

{% for page in site.pages %}
  * [{{page.title}}]({{page.url}})
{% endfor %}
