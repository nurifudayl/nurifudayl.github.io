---
layout: archive
title: "Book Chapters"
permalink: /publications/book-chapters/
author_profile: true
---

{% include publications-style.html %}

<p class="publications-intro">
A complete list of my book chapters.
</p>

{% assign chapters = site.publications | where: "category", "book-chapters" | sort: "date" | reverse %}

{% for post in chapters %}
  {% include publication-card.html item=post type="Book Chapter" link_label="Link" %}
{% endfor %}
