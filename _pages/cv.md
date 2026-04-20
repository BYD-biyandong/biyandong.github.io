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
* Ph.D in Geological Engineering, Tongji University, 2019-2025 (Supervisor: Professor Huang Yu)
* B.S. in Environmental Engineering , Ocean University of China, 2015-2019 (Supervisor: Professor Shan Hongxian)

Work experience
======
* 2025.7-2027.7: Postdoctoral research
  * Ocean University of China
  * Co-supervisor: Professor Jia Yonggang
  
Research interests 
======
* Submarine landslides 
* Wave-induced liquefaction
* Seabed or submarine slope instability
* Numerical simulation
  * DEM
  * CFD-DEM

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
<!-- 屏蔽列表页的摘要显示  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
