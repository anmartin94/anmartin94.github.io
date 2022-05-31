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
* B.S. in Computer Science, Northern Michigan University, 2020
* M.S. in Computer Science, University of Minnesota Duluth, 2022

Work experience
======
* Summer 2019: Software Engineering Intern
  * Datastax
  * Built a system health and performance reporting system in Java that collected throughput and latency metrics from multiple components of the code base. Wrote a program to send statistics to a dashboard and organized data so that the system's performance could be observed at a glance by team members.
  * Supervisor: Zach Kurey

* 2020-2022: Teaching Assistant
  * University of Minnesota Duluth
  * Duties included: Instructing labs, holding discussion sessions, helping students during office hours
  * Courses: Computer Science II, Software Analysis and Design, Computer Ethics, Computer Architecture, Natural Language Processing I
  * Supervisor: Dr. Arshia Khan
  
Skills
======
* Languages:
  * Python
  * Java
  * C++
* Tools:
  * PyTorch
  * spaCy
  * Stanford Core NLP
  * HuggingFace
* Natural Language Processing:
  * text classification
  * information extraction
* Other:
  * LaTeX

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
