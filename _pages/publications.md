---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

You can find all my publications [here](https://scholar.google.com/citations?hl=en&user=Wt9FiQEAAAAJ&view_op=list_works&sortby=pubdate)

## Selected List of Representative Papers

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
