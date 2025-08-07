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
* Ph.D from University of Science and Technology of China, 2024, Supervisor: Wen Huang
   
* B.S. from Qufu Normal University, 2019

Work experience
======
  * October 2024: Professor (Assistant) 
    Polish Academy of Sciences
    Supervisor: Yonatan Gutman

  * May 2024: Postdoctoral Fellow
    Dalian University of Technology
    Supervisor: Zhenxin Liu 


  
Skills
======
* Dynamical systems, Ergodic theory, Combinatorics


Selected Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
 Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
{% comment %}
## Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endcomment %}

{% comment %}
## Service and leadership
======
* 
{% endcomment %}
