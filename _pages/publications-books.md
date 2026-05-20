---
layout: archive
title: "Books"
permalink: /publications/books/
author_profile: true
---

{% include publications-style.html %}

<p class="publication-back-link">
  <a href="/publications/">← Back</a>
</p>

<p class="publications-intro">
A complete list of my books.
</p>

{% assign books = site.publications | where: "category", "books" | sort: "date" | reverse %}

<div class="pub-grid">
{% for post in books %}
  {% include publication-card.html item=post type="Book" link_label="Publisher / Link" %}
{% endfor %}
</div>
