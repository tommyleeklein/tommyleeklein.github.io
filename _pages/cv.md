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
* Ph.D, Mathematics, Aix-Marseille University / Institut Mathématiques de Marseille, in progress, 2024-2027 
* Master of Science, Mathematics, Sorbonne University, 2022-2024
* Bachelor of Science, Mathematics, Aix-Marseille University, 2019-2022
  
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
  
