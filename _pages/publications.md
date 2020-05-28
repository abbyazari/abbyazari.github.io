---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
This page includes highlighted publications. You can find the full list of published works at <a href="https://scholar.google.com/citations?hl=en&user=UdcGQbYAAAAJ"> Google Scholar.</a>

## Current manuscripts under review: 

* Liemohn, M. W., **Azari, A. R.**, Ganushkina, N. Y., and Rastatter, L. "The STONE curve: A ROC-derived model performance assessment tool". *Submitted in 2020*. Preprint acessible at <a href="https://www.essoar.org/doi/10.1002/essoar.10502020.1"> ESSOAr</a>.

* Dewey, R. M., Slavin, J., Raines, J. **Azari, A. R.**, and Sun, W. "MESSENGER observations of flow braking and flux pileup of dipolarizations in Mercury's magnetotail: Evidence for current wedge formation". *Submitted in 2020*.

## Accepted:

### 2020

* **Azari, A. R.**, Lockhart, J. W., Liemohn, M. W., and Jia, X. "Incorporating Physical Knowledge into Machine Learning for Planetary Space Physics".

### 2019

* **Azari, A. R.**, Jia, X., Liemohn, M. W., Hospodarsky, G. B., Provan, G., Ye, S. ‐Y., et al (2019). "Are Saturn's Interchange Injections Organized by Rotational Longitude?"Journal of Geophysical Research: Space Physics, 124. https://doi.org/10.1029/2018JA026196

### 2018

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
