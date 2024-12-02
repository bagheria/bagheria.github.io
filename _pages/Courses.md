---
layout: archive
title: "Courses"
permalink: /courses/
author_profile: true
---

Ayoub develops, coordinates, and instructs a range of courses, delving into the areas of Data Science, Data Analysis and Visualization, Text Mining, and Natural Language Processing. He is also the coordinator of the Applied Data Science master profile at Utrecht University. 

All his teachings is open employing both Python and R programming in data science. Beyond his regular curriculum, he extends his expertise through coordinating and leading summer courses as well as dynamic one-day workshops and teaching for professionals (OvP).

Here is a curated list of some of the courses he offers:

* [Data Wrangling and Data Analysis](https://infomdwr.nl/)
* [Battling the Curse of Dimensionality](https://infomda2.nl/)
<!--[Applied Data Science and Visualization](https://adav-course-2023.netlify.app/)-->
* [Text Mining with R](https://utrechtsummerschool.nl/courses/social-sciences/data-science-introduction-to-text-mining-with-r) 
* [Applied Text Mining](https://utrechtsummerschool.nl/courses/social-sciences/data-science-applied-text-mining)
* [Text Analysis with Python](https://utrechtsummerschool.nl/courses/social-sciences/text-analysis-with-python-online-course)
* [Transformers and Foundation Models](https://ayoubbagheri.nl/transformers/)

{% include base_path %}

{% for post in site.courses reversed %}
  {% include archive-single.html %}
{% endfor %}
