---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

[Download Abstracts](https://zdinakmg.github.io/files/zdinakmg_abstract.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
