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
* B.A. in Linguistics, University of Winchester, 2017
* M.A. in Applied Linguistics, University of Nottingham, 2018
* M.A. in Computational Linguistics,  University of Wolverhampton, 2019
* Ph.D. in Information Technology, Natural Language Processing, George Mason University, 2024 (expected)

Relevant Work Experience
======

* 2020-Present: Research and Teaching Assistant
  * Taught introductory undergraduate and postgraduate classes in linguistics and NLP.
  * Implemented ML models for various NLP-related tasks.
  * Participated in numerous international competitions (shared-tasks).
  * Published multiple papers.

* 2019-2020: Data Analyst
  * Researched, interpreted and manipulated data using a variety of systems whilst identifying issues for further analysis
  * Worked effectively with large volumes of complex and varied data. This data was then presented clearly to colleagues at various levels both expert and non-expert.
  * Wrote numerous python scripts to automatically classify data allowing for faster data processing and quality checking.

Skills
======
* Proficient in Python, Java, and R, including the use of various NLP toolkits.
* Extensive linguistic knowledge: Phonology, Phonetics, Semantics, Syntax, Morphology.
* Expertise in ML models for NLP: SVMs, Random Forests, Deep Learning, Transformers.
* Familiarity with rule-based and statistical machine translation systems: GramTrans and Moses.
* Experience with corpus and data analysis software: Wordsmith, AntConc, Tableau.
* Fascination with Sino-Tibetan languages: Mandarin and Cantonese.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
