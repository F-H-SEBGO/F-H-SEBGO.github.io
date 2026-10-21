---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. candidate**, Geology & Sustainable Mining Institute (GSMI), Mohammed VI Polytechnic University (UM6P), Ben Guerir, Morocco — 2024 to present
  * Thesis topic: stochastic simulation and machine learning for mineral resource estimation
<!-- Add your previous degrees here, newest first, e.g.
* **M.Sc. in ...**, University, City, Country — year
* **B.Sc. in ...**, University, City, Country — year
-->

Research skills
======
* Geostatistics: variography, kriging, Sequential Gaussian Simulation (SGS), Sequential Indicator Simulation (SIS)
* Monte Carlo methods and Markov chains
* Machine learning for geological and resource modelling
* Uncertainty quantification

Software and programming
======
* Python, R (ggplot2), LaTeX
* Isatis.neo

Languages
======
* French, English

{% assign pub_count = site.publications | size %}
{% if pub_count > 0 %}
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
