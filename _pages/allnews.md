---
title: "News"
layout: textlay
excerpt: "Josefowicz Lab at Weill Cornell Medicine"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
