---
layout: default
title: Sprecher Büro
permalink: Speaker.html
---

# Sprecher Büro





{% for speaker in site.speakers %}
​    <li>
​      <a href="{{ speaker.url }}">{{ speaker.title }}</a>
​    </li>
{% endfor %}