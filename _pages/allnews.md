---
title: "News"
layout: textlay
excerpt: "SBUWear Research Group at Stony Brook University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
