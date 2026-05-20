---
layout: archive
title: "Book Chapters"
permalink: /publications/book-chapters/
author_profile: true
---

{% include publications-style.html %}

<p class="publication-back-link">
  <a href="/publications/">← Back</a>
</p>

<p class="publications-intro">
A complete list of my book chapters.
</p>

{% assign chapters = site.publications | where: "category", "book-chapters" | sort: "date" | reverse %}

{% if chapters.size > 0 %}
<div class="pub-list">
{% for post in chapters %}
  {% include publication-card.html item=post type="Book Chapter" link_label="Link" %}
{% endfor %}
</div>
{% else %}
<p class="publications-intro">
No book chapters have been added yet.
</p>
{% endif %}
