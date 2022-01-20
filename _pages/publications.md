---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Here is a short list of my publications, for a more comprehensive list please visit my [Google Scholar page](https://scholar.google.nl/citations?user=QWhiQdgAAAAJ&hl=en).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
