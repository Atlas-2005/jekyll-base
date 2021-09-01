---
layout: default
title: About
---

# About page

This page tells you a little bit about me.

<h1>Staff</h1>

# Code Below is for staff list
<ul>
  {% for author in site.authors %}
  <li>
    <h2>
      <a href="{{ author.url }}">{{ author.display_name }}</a>
    </h2>
    <h3>{{ author.position }}</h3>
    <p>{{ author.content | markdownify }}</p>
  </li>
  {% endfor %}
</ul>
