---
layout: page
title: It even works!
tagline: 
---
{% include JB/setup %}

## What's new?

Here's a list of random things I've been writing about:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


