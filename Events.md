---
layout: default
title: Events
permalink: Events.html
---

# Events

## Kommende Veranstaltungen

{% for event in site.events %}
​    <li>
​      <a href="{{ event.url }}">{{ event.title }}</a>
​    </li>
{% endfor %}

## Bisherige Veranstaltungen

{% for event in site.events %}
​    <li>
​      <a href="{{ event.url }}">{{ event.title }}</a>
​    </li>
{% endfor %}