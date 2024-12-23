---
layout: archive
title: "Short CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---



<a href="/files/cv.pdf" download>Download my full CV here</a>
---
{% include base_path %}
Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

Publications
======

<b>Journal Articles</b>

<ul>
  {% for post in site.publications reversed %}
    {% if post.category == "manuscripts" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>

<b>Book Chapters</b>

<ul>
  {% for post in site.publications reversed %}
    {% if post.category == "conferences" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>

<b>Other Publications</b>

<ul>
  {% for post in site.publications reversed %}
    {% if post.category == "books" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>
  
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
