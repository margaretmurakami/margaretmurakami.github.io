---
title: "Posts"
layout: default
permalink: "projects/"
author_profile: true
comments: true
share: true
related: true

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
