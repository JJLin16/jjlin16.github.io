---
title: Photography
permalink: /photography/
layout: single
---


---

Here is my collection of nature photos:

<ul>
{% for item in site.nature %}
  <li>
    <a href="{{ item.url }}">{{ item.title }}</a>
  </li>
{% endfor %}
</ul>)


