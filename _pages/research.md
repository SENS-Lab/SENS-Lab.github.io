---
title: "SENS Lab - Research"
layout: research
excerpt: "SENS Lab at The Ohio State University"
sitemap: false
permalink: /research/
---

## Researchlj


{% assign number_printed = 0 %}
{% for member in site.data.projects %}

{% assign even_odd = number_printed | modulo: 3 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/projectpic/{{ member.photo }}" class="img-responsive" width="100%" style="float: left" />
  <h4>{{ member.name }}</h4>
  {{ member.education2 }}
  <ul style="overflow: hidden">
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 3 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}
