---
title: "News"
layout: textlay
excerpt: "Black Hole Group at IAA."
sitemap: false
permalink: /allnews.html
---

# News

{% assign number_printed = 0 %}
{% for member in site.data.news %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<!--
{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
-->
