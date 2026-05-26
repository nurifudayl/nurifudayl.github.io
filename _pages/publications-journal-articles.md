---
layout: archive
title: "Journal Articles"
lang: en
permalink: /publications/journal-articles/
author_profile: true
translations:
  en: "/publications/journal-articles/"
  tr: "/tr/publications/journal-articles/"
  fr: "/fr/publications/journal-articles/"
---

{% include publications-style.html %}

<p class="publication-back-link">
  <a href="{{ '/publications/' | relative_url }}">← Back</a>
</p>

{% assign articles = site.publications | where: "category", "journal-articles" | sort: "date" | reverse %}

{% if articles.size > 0 %}
<div class="pub-list">
{% for post in articles %}
  {% include publication-card.html item=post link_label="DOI / Link" details_label="Details" %}
{% endfor %}
</div>
{% else %}
<p class="publications-intro">
No journal articles have been added yet.
</p>
{% endif %}
