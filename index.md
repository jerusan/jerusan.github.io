---
layout: default
title: Home
---

# Welcome to My Blog

I'm Jerusan – a systems thinker, software engineer, and curious mind building tools like [DevSkill](#) and [Reality Layer](#).

Here, I share thoughts on engineering, complexity, and designing tools that help humans think better.

## Recent Posts
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%B %-d, %Y" }}</li>
  {% endfor %}
</ul>
