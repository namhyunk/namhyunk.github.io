---
permalink: /publications/
title: "Publications"
author_profile: true
---

## Journal Articles

{% for post in site.publications %}
  {% if post.category == "manuscripts" %}
    <div class="publication-item">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="authors">{{ post.authors }}</p>
      <p class="venue"><em>{{ post.venue }}</em>, {{ post.date | date: "%B %Y" }}</p>
      {% if post.paperurl %}
        <p><a href="{{ post.paperurl }}" target="_blank">Paper Link</a></p>
      {% endif %}
      {% if post.excerpt %}
        <p>{{ post.excerpt }}</p>
      {% endif %}
    </div>
    <hr>
  {% endif %}
{% endfor %}

## Conference Papers

{% for post in site.publications %}
  {% if post.category == "conferences" %}
    <div class="publication-item">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="authors">{{ post.authors }}</p>
      <p class="venue"><em>{{ post.venue }}</em>, {{ post.date | date: "%B %Y" }}</p>
      {% if post.paperurl %}
        <p><a href="{{ post.paperurl }}" target="_blank">Paper Link</a></p>
      {% endif %}
      {% if post.excerpt %}
        <p>{{ post.excerpt }}</p>
      {% endif %}
    </div>
    <hr>
  {% endif %}
{% endfor %}

## Preprints

{% for post in site.publications %}
  {% if post.category == "preprints" %}
    <div class="publication-item">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="authors">{{ post.authors }}</p>
      <p class="venue"><em>{{ post.venue }}</em>, {{ post.date | date: "%B %Y" }}</p>
      {% if post.paperurl %}
        <p><a href="{{ post.paperurl }}" target="_blank">Paper Link</a></p>
      {% endif %}
      {% if post.excerpt %}
        <p>{{ post.excerpt }}</p>
      {% endif %}
    </div>
    <hr>
  {% endif %}
{% endfor %}




