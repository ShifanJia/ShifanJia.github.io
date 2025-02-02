---
layout: archive
title: "Research"
permalink: /Researchs/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{(https://scholar.google.ca/citations?hl=en&user=d4s_U0kAAAAJ)}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
