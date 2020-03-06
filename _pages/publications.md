---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
This page includes highlighted publications. You can find the full list at my <a href="https://scholar.google.com/citations?hl=en&user=UdcGQbYAAAAJ"> Google Scholar.</a>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
