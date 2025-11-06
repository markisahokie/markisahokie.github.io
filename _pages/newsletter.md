---
layout: default
title: Newsletter
permalink: /newsletter/
---

# ALPFA Gotham City Newsletter

Welcome to our newsletter page. Below you can subscribe or view all past issues.

<!-- Link to the newsletters collection index -->
<p><a href="{{ '/newsletters/' | relative_url }}">View All Newsletters</a></p>

<!-- Subscription Form (placeholder - requires backend to actually collect emails) -->
<form>
  <h3>Subscribe to Our Newsletter</h3>
  <label for="email">Email Address:</label>
  <input type="email" id="email" name="email" required>
  <button type="submit" class="btn">Subscribe</button>
</form>

<!-- Optional: show recent issues inline -->
{% if site.newsletters and site.newsletters.size > 0 %}
  <h2>Recent Issues</h2>
  <ul>
    {% for newsletter in site.newsletters limit:5 %}
      <li><a href="{{ newsletter.url | relative_url }}">{{ newsletter.title }}{% if newsletter.date %} — {{ newsletter.date | date: "%B %d, %Y" }}{% endif %}</a></li>
    {% endfor %}
  </ul>
{% endif %}
