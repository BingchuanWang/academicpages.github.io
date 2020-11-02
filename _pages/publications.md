---
layout: archive
title: "Publications ([Google Scholar](https://scholar.google.com.hk/citations?user=jgNTXn0AAAAJ&hl=zh-CN))"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
