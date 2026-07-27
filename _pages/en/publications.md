---
layout: archive
permalink: /en/publications/
author_profile: true
lang: en
translation_url: /publications/
source_collection: pages
translation_key: page-publications
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% include bilingual-entry-content.html %}
