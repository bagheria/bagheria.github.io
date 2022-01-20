---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Here is a short list of my publications, 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
