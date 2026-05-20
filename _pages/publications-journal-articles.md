---

{% include publications-style.html %}

<p class="publication-back-link">
  <a href="/publications/">← Back</a>
</p>

<p class="publications-intro">
A complete list of my journal articles.
</p>

{% assign articles = site.publications | where: "category", "journal-articles" | sort: "date" | reverse %}

<div class="pub-list">
{% for post in articles %}
  {% include publication-card.html item=post type="Journal Article" link_label="DOI / Link" %}
{% endfor %}
</div>
