---
layout: page
title: Seminar calendar	
permalink: /seminar/
---

### Nonlinear waves and microlocal analysis seminar

In Fall 2026, the seminar meets in Blocker 302.

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li>{{ post.date | date_to_string }}: <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
