---
layout: home
---

{% for post in site.post %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
