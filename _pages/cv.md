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
------
* Ph.D in Computer Science, Macquarie University(Australia), 2017-2020
* M.S. in Computer Science and Technology, Soochow University(China), 2013-2016

Work experience
------
* 2022 - Current: Algorithm Expert
  * Ant Group
  * Duties included: Search and recommender systems & LLM-Based Agent & LLM Training 

* 2020 - 2021: Senior Algorithm Engineer
  * Ant Group
  * Duties included: Search and recommender systems

Publications
------
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
------
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
------
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
