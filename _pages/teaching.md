---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

I teach courses about Data Science, Data Analysis and Visualisation, Text Mining, and Natural Language Processing. I use both Python and R in my teaching. My courses are open source and you can contact me for the source if you are interested in one of my lectures.

I also summer courses and one-day workshops. I highly recommend the courses in Applied Data Science speciality at Urecht Summer School, especially the two courses that I teach on TextMining:
* [Introduction to Text Mining with R](https://utrechtsummerschool.nl/courses/social-sciences/data-science-introduction-to-text-mining-with-r) 
* [Applied Text Mining](https://utrechtsummerschool.nl/courses/social-sciences/data-science-applied-text-mining)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
