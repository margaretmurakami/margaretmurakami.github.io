---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## News

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>
<p>{{ article.headline }}</p>
<p>{{ article.video_link }}</p>

{% endfor %}
</div>