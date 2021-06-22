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
* B.S. in Computer Science, Ohio University, 2011-2015
* B.S. in Electrical Engineering, Ohio University, 2011-2015
* M.S. in Computational Linguistics, University of Washington, 2017-2019
* PhD in Computer Science, University of Maryland, 2021-

Work experience
======
* 2015-Present: Computational Linguist, [MITRE](https://www.mitre.org/)

Fellowships and Awards
======
* 2021-2022: NIST PREP Fellowship

{% if site.publications.size != 0 %}    
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}

{% if site.talks.size != 0 %}  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
{% endif %}
  
{% if site.teaching.size != 0 %}  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
