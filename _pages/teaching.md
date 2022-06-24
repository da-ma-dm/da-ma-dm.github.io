---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

- Co-Instructor, ENSC 813/413, Deep Learning Systems in Engineering 
  Simon Fraser University, School of Engineering Science 2021

- Co-Instructor, MSc. Advanced Biomedical Imaging.
  University College London, Center for Advanced Biomedical Imaging 2016 



{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
