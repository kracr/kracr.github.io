---
title: "News"
layout: textlay
excerpt: "KRaCR Labs @IIIT Delhi"
sitemap: false
permalink: /allnews.html
---

# News


{% for article in site.data.news.news_2020 %}
<em>{{ article.headline }}</em><br><span style="color:#7c66ac;">Posted on {{ article.date }}</span>
{% endfor %}

{% for article in site.data.news.news_2019 %}
<em>{{ article.headline }}</em><br><span style="color:#7c66ac;">Posted on {{ article.date }}</span>
{% endfor %}

{% for article in site.data.news.news_2018 %}
<em>{{ article.headline }}</em><br><span style="color:#7c66ac;">Posted on {{ article.date }}</span>
{% endfor %}