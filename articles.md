---
layout: page
title: Articles
permalink: /articles/
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h2>
        <a class="post-link" href="http://walkman100.github.io/fna-xna.github.io{{ post.url }}">{{ post.title }}</a>
      </h2>

      {{ post.excerpt }}
    
      <span class="post-meta"><span class="post-meta-author">{{ post.author }}</span> <span class="post-meta-date">{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
