---
layout: page
title: "Publications"
permalink: /publications/
---

<h1>Publications</h1>

<ul class="publication-list">
  {% for post in site.categories.paper %}
    {% if post.image %}
      <li class="publication-item">
        <a href="{{ post.url | relative_url }}">
          <img
            src="{{ post.image | relative_url }}"
            alt="{{ post.title }}"
            class="publication-thumb">
          <p class="publication-title">{{ post.title }}</p>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>