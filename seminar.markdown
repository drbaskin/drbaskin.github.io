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
      <li>{{ post.title }}<br>
      {{ post.content }}</li>
    {% endfor %}
  </ul>
{% endfor %}
