---
layout: page
title: News
description: 
image: 
nav-menu: true
---

# Highlights of our QuantaMap journey
For regular updates, follow our [LinkedIn page](https://www.linkedin.com/company/quantamap/)

[Name of Link]({% post_url 2025-06-01-MKB-QUACIMI %})

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


