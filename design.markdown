---
layout: default
title: Design Work
permalink: /design/
---
# Design Work

<ul>
{% for project in site.design %}
    <li><a href="{{project.url}}">{{project.title}}</a></li>
{% endfor %}
</ul>