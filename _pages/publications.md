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
<ol>

{% for post in site.publications reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}

{% for post in site.preprints reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}

{% for post in site.inPreparation reversed %}
  <li>{% include archive-single.html %}</li>
{% endfor %}

</ol>




