---
layout: default
title: Sprecher Büro
permalink: Speaker.html
---

# Sprecher Büro





{% for item in site.speakers %}
​    <li>
​      <a href="{{ item.url }}">{{ item.title }}</a>
​    </li>
{% endfor %}