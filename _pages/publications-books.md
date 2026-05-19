---
layout: archive
title: "Books"
permalink: /publications/books/
author_profile: true
---

{% include publications-style.html %}

<p class="back-link">
  <a href="/publications/">← Back to Publications</a>
</p>

{% assign books = site.publications | where: "category", "books" | sort: "date" | reverse %}

{% for post in books %}
  {% include publication-card.html item=post type="Book" link_label="Publisher / Link" %}
{% endfor %}
