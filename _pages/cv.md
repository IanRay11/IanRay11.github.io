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
* Ph.D in Computer Science, 2025 (expected)
* M.S. in Mathematics, Western Kentucky University, 2022
* B.S. in Mathematics and Physics, Morehead State University, 2019

Work experience
======
* Fall 2025 - present: Associate Instructor
  * Indiana University Bloomington

* Spring 2022 - Summer 2025: Private tutor
  * Independent
  * Duties include: Private math tutoring

* Fall 2020 - Spring 2022: Teaching Assistant
  * Western Kentucky University
  * Duties includes: Lead recitation 

* Fall 2015-2019: Department tutor
  * Morehead State University
  * Duties included: Running math department tutoring lab
  * Supervisor: Denise Patrick

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
