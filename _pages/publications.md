---
title: "KRaCR Lab - Publications"
layout: gridlay
excerpt: "KRaCr Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

<h3 style="color:purple;"><b>2020</b></h3>
{% for publi in site.data.publications.publications_2020 %}

  
<b>{{ publi.title }}</b> <br />  <em>{{ publi.authors }} </em> <br /><a style="color:#7c66ac;" href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

<h3 style="color:purple;"><b>2019</b></h3>
{% for publi in site.data.publications.publications_2019 %}

  
<b>{{ publi.title }}</b> <br />  <em>{{ publi.authors }} </em> <br /><a style="color:#7c66ac;" href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}


<h3 style="color:purple;"><b>2018</b></h3>
{% for publi in site.data.publications.publications_2018 %}

  
<b>{{ publi.title }}</b> <br />  <em>{{ publi.authors }} </em> <br /><a style="color:#7c66ac;" href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}