---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
This page includes highlighted publications. You can find the full list of published works at <a href="https://scholar.google.com/citations?hl=en&user=UdcGQbYAAAAJ"> Google Scholar.</a>

## Current manuscripts under review: 

* **Azari, A. R.**, Lockhart, J. W., Liemohn, M. W., and Jia, X. "Incorporating Physical Knowledge into Machine Learning for Planetary Space Physics". *Submitted in 2020*.

* Liemohn, M. W., **Azari, A. R.**, Ganushkina, N. Y., and Rastatter, L. "The STONE curve: A ROC-derived model performance assessment tool". *Submitted in 2020*. Preprint acessible at <a href="https://www.essoar.org/doi/10.1002/essoar.10502020.1"> ESSOAr</a>.

* **Azari, A. R.**, Allen, R. C., Liemohn, M. W., Jia, X., Dewey, R. M., Mitchell, D. G., Paranicas, C., and Sergis, N. "System Wide Evidence of Particle Loss and Acceleration around Saturn". *Submitted in 2020*.

## In print:

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
