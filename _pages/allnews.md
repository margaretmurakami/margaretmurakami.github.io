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

{% if article.link %}
    <p>Article Link: <a href="{{ article.link }}">Read more</a></p>
{% endif %}
{% if article.video_link %}
    <p>Video Link: <a href="{{ article.video_link }}">Watch video</a></p>
{% endif %}
{% endfor %}
</div>
