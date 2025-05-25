---
title: mirror
layout: null
---
{% for file in site.static_files %}
<a href="{{ file.path }}">{{ file.name }}</a><br>
{% endfor %}