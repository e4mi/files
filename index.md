---
layout: none
title: mirror
---
{% for file in site.static_files %}
{% if file.path == '/' | append: file.name %}
<a href="{{ file.path }}">{{ file.name }}</a><br>
{% endif %}
{% endfor %}