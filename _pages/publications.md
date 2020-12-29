---
title: "KRaCR Lab - Publications"
layout: gridlay
excerpt: "KRaCr Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications
<br />


{% for publi in site.data.publications.publications_2020 %}

{{ publi.authors }} {{ publi.title }} {{ publi.news2 }}  <a href="{{ publi.pdf }}">{{ publi.link.display }} <img src ="{{ publi.image }}"/></a>

{% endfor %}


{% for publi in site.data.publications.publications_2019 %}

{{ publi.authors }} {{ publi.title }} {{ publi.news2 }}  <a href="{{ publi.pdf }}">{{ publi.link.display }} <img src ="{{ publi.image }}"/></a>

{% endfor %}


{% for publi in site.data.publications.publications_2018 %}

{{ publi.authors }} {{ publi.title }} {{ publi.news2 }}  <a href="{{ publi.pdf }}">{{ publi.link.display }} <img src ="{{ publi.image }}"/></a>

{% endfor %}