---
layout: default
---

{% for post in site.posts %}
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
{% endfor %}
