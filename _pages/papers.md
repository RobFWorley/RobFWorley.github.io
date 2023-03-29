---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

Here is a set of papers that I have written.

You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.

TEST TEST TEST???

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  TEST TEST TEST TEST TEST
  {% include archive-single.html %}
{% endfor %}
