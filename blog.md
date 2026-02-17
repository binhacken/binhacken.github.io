---
layout: default
title: Blog
---

## Latest Posts

<ul>
{% for post in site.posts %}
<li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
</li>
{% endfor %}
</ul>
