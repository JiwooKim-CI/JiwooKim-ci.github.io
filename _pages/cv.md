---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PDF Embed Example</title>
</head>
<body>
    <h1>CV file</h1>
    <embed src="/files/Academic_CV_JK.pdf" type="application/pdf" width="100%" height="600px" />
</body>
</html>

{% include base_path %}

Education
======
* B.S. in Education, Ewha Womans University University, 2020
* M.S. in Educational Measurement and Evaluation, Seoul National University, 2023
* Ph.D in Psychology / Minor in Applied Statistics, Cornell University, 2028 (expected)

Work experience
======
* Fall 2024 - Spring 2025: Research Assistant
  * Cornell University
  * Supervisor: Professor Felix Thoemmes

* 2022: Researcher
  * The Korea Chamber of Commerce and Industry
  * Duties included: Item development and validation
    
* Fall 2021: Research Assistant
  * Seoul National University
  * Duties included: Item development and validation, Analyzed current academic resilience competency of undergraduate school students
  * Supervisor: Professor Sun-Geun Baek
 
  
Skills
======
* Quantitative method
* Statistical language
  * R
  * SPSS

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
  
Service and leadership
======
* Korean tutoring for North Korean defectors (2018)
* Career mentor for Children of Traffic Accident Victims (2016)
