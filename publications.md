---
layout: page
title: "Publications"
permalink: /publications/
---

<h1>Publications</h1>

<ul class="post-list">
  {% for post in site.categories.publication %}
    <li class="post-item">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      {% if post.date %}
        <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
      {% endif %}
      {% if post.excerpt %}
        <p>{{ post.excerpt }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul>