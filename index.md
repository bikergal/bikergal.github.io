---
layout: default
title: keep pedaling
---

# dailies

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">
  {{ post.date | date: "%-d %B %Y" }}
      </a>
    </li>
  {% endfor %}
</ul>

{% include custom-scripts.html %}

