---
title: "News"
layout: textlay
excerpt: "KRaCR Labs @IIIT Delhi"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
