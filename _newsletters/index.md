---
layout: post
title: Newsletters
permalink: /newsletters/
---

# Newsletters

{% if site.newsletters and site.newsletters.size > 0 %}
  <ul>
  {% for n in site.newsletters %}
    <li>
      <a href="{{ n.url | relative_url }}">{{ n.title }}</a>
      {% if n.date %} — {{ n.date | date: "%B %d, %Y" }}{% endif %}
    </li>
  {% endfor %}
  </ul>
{% else %}
  <p>No newsletters found.</p>
{% endif %}
