---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

{% include base_path %}

Here is a set of papers that I have written.

[Google Analytics Privacy Policy](http://www.google.com/analytics/learn/privacy.html)

You can also find my articles on [my Google Scholar profile]({{ author.googlescholar }})
TEST 1

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u> TEST 2
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
