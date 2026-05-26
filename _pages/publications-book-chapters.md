---
layout: archive
title: "Book Chapters"
lang: en
permalink: /publications/book-chapters/
author_profile: true
translations:
  en: "/publications/book-chapters/"
  tr: "/tr/publications/book-chapters/"
  fr: "/fr/publications/book-chapters/"
---

{% include publications-style.html %}

<p class="publication-back-link">
  <a href="{{ '/publications/' | relative_url }}">← Back</a>
</p>

{% assign chapters = site.publications | where: "category", "book-chapters" | sort: "date" | reverse %}

{% if chapters.size > 0 %}
<div class="pub-list">
{% for post in chapters %}
  {% include publication-card.html item=post link_label="Link" details_label="Details" %}
{% endfor %}
</div>
{% else %}
<p class="publications-intro">
No book chapters have been added yet.
</p>
{% endif %}
