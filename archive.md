---
layout: page
permalink: /posts/
title: "All posts"
crawlertitle: "All articles"
summary: "Posts about Humanity Torbay"
active: posts
---

<ul class="year">
  {% for post in site.posts %}	
      <li>
        {% if post.lastmod %}
              <a href="{{ post.url }}">{{ post.title }}</a>
              <span class="date">{{ post.lastmod | date: "%d-%m-%Y"  }}</span>
          {% else %}
              <a href="{{ post.url }}">{{ post.title }}</a>
              <span class="date">{{ post.date | date: "%d-%m-%Y"  }}</span>
        {% endif %}
      </li>
  {% endfor %}
</ul>