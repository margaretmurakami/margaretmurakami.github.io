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
    <p>Video link {% if article.video_link %}<a href="{{ article.video_link }}">here</a>{% endif %}</p>
  
  {% endfor %}
</div>

