---
title: "KRaCR Lab - Publications"
layout: gridlay
excerpt: "KRaCr Lab -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

<br />
<br />
<br />

<script type="text/javascript">

function myFunc(clicked_id)
{
	console.log(clicked_id)
}

</script>

{% for publi in site.data.publications.publications_2020 %}

- {{ publi.authors }} {{ publi.title }} {{ publi.news2 }}  <a href="{{ publi.pdf }}" download><img src =" {{ site.url }}{{ site.baseurl }}/images/application-pdf.png"/></a>

{% endfor %}

{% for publi in site.data.publications.publications_2019 %}

- {{ publi.authors }} {{ publi.title }} {{ publi.news2 }}  <a href="{{ publi.pdf }}" download><img src =" {{ site.url }}{{ site.baseurl }}/images/application-pdf.png"/></a>

{% endfor %}

{% for publi in site.data.publications.publications_2018 %}

- {{ publi.authors }} {{ publi.title }} {{ publi.news2 }}  <a href="{{ publi.pdf }}" download><img src =" {{ site.url }}{{ site.baseurl }}/images/application-pdf.png"/></a>

{% endfor %}
