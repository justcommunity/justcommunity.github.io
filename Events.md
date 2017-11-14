---
layout: default
title: Events
permalink: Events.html
---

# Events

## Kommende Veranstaltungen

<ul>
{% for event in site.events %}
​    <li>
​      <a href="{{ event.url }}">{{ event.title }}</a>
​    </li>
{% endfor %}
</ul>

## Bisherige Veranstaltungen

<ul>
{% for event in site.events %}
​    <li>
​      <a href="{{ event.url }}">{{ event.title }}</a>
​    </li>
{% endfor %}
</ul>