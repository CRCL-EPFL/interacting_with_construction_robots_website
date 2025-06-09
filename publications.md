---
layout: page
title: "Publications"
permalink: /publications/
---

<h1>Publications</h1>

<ul class="post-list">
  {% for post in site.categories.paper %}
    {% include post-list-item.html post=post %}
  {% endfor %}
</ul>