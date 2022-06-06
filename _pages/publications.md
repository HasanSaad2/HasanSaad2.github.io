---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Papers
====

{% for post in site.inPreparation reversed %}
  {% include archive-single.html %}
{% endfor %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}




