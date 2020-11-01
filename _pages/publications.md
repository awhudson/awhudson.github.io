---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Preprints
======
1. Hudson, A., & Shojaie, A. Covariate-Adjusted Inference for Differential Analysis of High-Dimensional Networks.
1. Hudson, A., & Shojaie, A. Statistical Inference for Qualitative Interactions with Applications to Precision Medicine and Differential Network Analysis.

Published
======
1. Culpepper, S. A., & Hudson, A. (2018). An Improved Strategy for Bayesian Estimation of the Reduced Reparameterized Unified Model. Applied psychological measurement, 42(2), 99–115.
1. Zeigler-Johnson, C., Hudson, A., Glanz, K., Spangler, E., & Morales, K. H. (2018). Performance of prostate cancer recurrence nomograms by obesity status: a retrospective analysis of a radical prostatectomy cohort. BMC cancer, 18(1), 1061.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
