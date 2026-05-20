---
layout: archive
title: "Journal Articles"
permalink: /publications/journal-articles/
author_profile: true
---

{% include publications-style.html %}

<p class="publication-back-link">
  <a href="/publications/">← Back</a>
</p>

<p class="publications-intro">
A complete list of my journal articles.
</p>

{% assign articles = site.publications | where: "category", "journal-articles" | sort: "date" | reverse %}

{% if articles.size > 0 %}
<div class="pub-list">
{% for post in articles %}
  {% include publication-card.html item=post type="Journal Article" link_label="DOI / Link" %}
{% endfor %}
</div>
{% else %}
<p class="publications-intro">
No journal articles have been added yet.
</p>
{% endif %}
