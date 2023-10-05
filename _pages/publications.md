---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [My Google Scholar](https://scholar.google.com/citations?user=Gvs5nz8AAAAJ)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
