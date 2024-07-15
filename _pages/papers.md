---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

{% include base_path %}

Here is a set of papers that I have written.

You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{{author.googlescholar}}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
