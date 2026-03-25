---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Employment

* **2021 – present:** Assistant Professor, Psychological Methods, University of Amsterdam
* **2015 – 2021:** PhD Researcher, Psychological Methods, University of Amsterdam

## Education

* **PhD** in Psychological Methods, University of Amsterdam, 2021
* **MSc** in Psychology (Psychological Methods), University of Amsterdam
* **BSc** in Psychology, University of Amsterdam

## Book

* Field, A. P. & van Doorn, J. B. (2025). *Discovering Statistics Using JASP*. SAGE Publications. Companion website: [discoverjasp.com](https://discoverjasp.com)

## Skills & Expertise

* Bayesian statistics and hypothesis testing
* Statistical software development (JASP, R)
* Open science practices
* Quantitative data analysis
* Teaching and curriculum development

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Projects

  <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
