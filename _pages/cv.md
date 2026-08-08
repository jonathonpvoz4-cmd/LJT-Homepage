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
* Ph.D. in Computer Science (2024-Present)
  * Hong Kong University of Science and Technology (HKUST)
  * Advisor: Professor Junxian He
* B.Eng. (2020-2024)
  * Shanghai Jiao Tong University (SJTU)
  * Received Zhiyuan Honor Scholarship

Work experience
======
* Research Intern (February 2025 - Present)
  * MINIMAX

* Research Intern (June 2024 - September 2024)
  * Tencent WXG
  * Advisor: Zifei Shan

* Research Intern (June 2023 - December 2023)
  * Shanghai AI Lab
  * Advisor: Prof. Yu Cheng

Skills
======
* Python
* PyTorch
* Jekyll
* LaTeX
* Git

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer for NeurIPS, ICML, ICLR, ACL, EMNLP
