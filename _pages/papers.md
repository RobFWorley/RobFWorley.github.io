---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

{% include base_path %}

Here is a set of papers that I have written.

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u> 
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
