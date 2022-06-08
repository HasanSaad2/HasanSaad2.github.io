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

{% for post in site.publications %}
  <li>{% include archive-single.html %}</li>
{% endfor %}

{% for post in site.preprints %}
  <li>{% include archive-single.html %}</li>
{% endfor %}

{% for post in site.inPreparation %}
  <li>{% include archive-single.html %}</li>
{% endfor %}

</ol>




