---
layout: page
title: DIALOGUE 2018
subtitle: Ashoka Art Gallery Alumni Weekender Exhibition
use-site-title: true
---
  <h1> List of artists this year - </h1>
<ul>
    {% for item in site.people %}
  <li><p><a href="{{ item.url }}">{{ item.title }}</a> </p></li>
  <p></p>
{% endfor %}

</ul>