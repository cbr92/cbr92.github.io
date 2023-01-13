---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

M. Avella-Medina, C. Bradshaw, and P.L. Loh. Differentially private inference via noisy optimization. (Submitted). [[arXiv]](https://arxiv.org/abs/2103.11003)

C. Bradshaw and W. Tansey. Identifying Spatial Biomarkers from Cellular Imaging Data. *International Conference on Machine Learning Workshop on Computational Biology*, 2022. [[workshop]](https://icml-compbio.github.io/#papers)

