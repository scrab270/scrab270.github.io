---
layout: default
title: GIS & Planning Work
permalink: /gis/
---
# GIS & Planning Work

<ul>
{% for project in site.gis %}
    <li><a href="{{project.url}}">{{project.title}}</a></li>
{% endfor %}
</ul>