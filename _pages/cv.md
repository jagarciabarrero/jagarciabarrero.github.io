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
* Ph.D in Economic History, University of Barcelona, University Carlos III of Madrid & University of Valencia, July 2022
* M.S. in Economic History, University of Barcelona, September 2016
* B.S. in History, University of the Balearic Islands, July 2015

Work experience
======
* Winter 2025-: Margalida Comas Postdoctoral Researcher
  * University of the Balearic Islands

* Spring 2017 - Fall 2021: FPI - Predoctoral Researcher
  * University of Barcelona

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
