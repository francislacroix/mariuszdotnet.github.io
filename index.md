---
layout: default
---

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a> - ({{ post.date | date: "%m.%d.%Y" }})</h3>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>