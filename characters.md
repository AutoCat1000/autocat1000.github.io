---
layout: default
title: CHARACTERS
---
{% for post in site.characters %}
    <a href="{{ post.url | absolute_url }}">
      {{ post.title }}
    </a>
{% endfor %}
