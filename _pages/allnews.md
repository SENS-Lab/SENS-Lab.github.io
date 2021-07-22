---
title: "SENS Lab - News"
layout: textlay
excerpt: "SENS Lab at The Ohio State University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
