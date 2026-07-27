---
layout: archive
permalink: /en/cv/
author_profile: true
lang: en
translation_url: /cv/
source_collection: pages
translation_key: page-cv
---

{% include bilingual-entry-content.html field="body_en_before_publications" %}

Publications
======

<ul>{% for post in site.publications %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

{% include bilingual-entry-content.html field="body_en_after_publications" %}
