---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

Here is a set of papers that I have written.

You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
TEST 1

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
	TEST 2
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
