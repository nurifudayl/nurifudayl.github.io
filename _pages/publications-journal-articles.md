---
layout: archive
title: "Journal Articles"
permalink: /publications/journal-articles/
author_profile: true
---

{% include publications-style.html %}

{% assign articles = site.publications | where: "category", "journal-articles" | sort: "date" | reverse %}

{% for post in articles %}
  {% include publication-card.html item=post type="Journal Article" link_label="DOI / Link" %}
{% endfor %}
