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
        <p>Article link <a href="{{ article.link }}">here</a></p>
    {% endif %}
  
    {% if article.video_link %}
        <p>Video link <a href="{{ article.video_link }}">here</a></p>
    {% endif %}
  
  {% endfor %}
</div>

