---
layout: archive
title: "Books"
lang: en
permalink: /publications/books/
author_profile: true
translations:
  en: "/publications/books/"
  tr: "/tr/publications/books/"
  fr: "/fr/publications/books/"
---

{% include publications-style.html %}

<p class="publication-back-link">
  <a href="{{ '/publications/' | relative_url }}">← Back</a>
</p>

{% assign books = site.publications | where: "category", "books" | sort: "date" | reverse %}

{% if books.size > 0 %}
<div class="pub-list">
{% for post in books %}
  {% include publication-card.html item=post link_label="Publisher / Link" details_label="Details" %}
{% endfor %}
</div>
{% else %}
<p class="publications-intro">
No books have been added yet.
</p>
{% endif %}
