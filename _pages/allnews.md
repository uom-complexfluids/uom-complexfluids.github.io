---
title: "News"
layout: textlay
excerpt: "Complex Fluids Group at the University of Manchester."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
