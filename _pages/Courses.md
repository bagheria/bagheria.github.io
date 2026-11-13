---
layout: archive
title: "Courses"
permalink: /courses/
author_profile: true
---

I develop, coordinate, and teach a range of courses, delving into the areas of Machine Learning, Data Science, 
and Natural Language Processing. I am also coordinator of the AI/Applied Data Science education at MSDS at Utrecht University. 

Here is a list of my recent teaching:

* [Machine Learning](https://daml.robertab.nl), master level
* Data Wrangling and Data Analysis, master level
* Battling the Curse of Dimensionality, master level
* Applied Text Mining & NLP, summerschool
* Transformers and Foundation Models, teaching for professionals

{% include base_path %}

{% for post in site.courses reversed %}
  {% include archive-single.html %}
{% endfor %}
