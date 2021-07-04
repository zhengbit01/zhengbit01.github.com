---
layout: page
title: Storage World!
tagline: Supporting tagline
---

Check it out [storage world](index.html)

## Update _config file

In `_config.yml` update configuration.
    
The theme should reference these variables whenever needed.
    
## Posts

Add posts which will show here.

Here's the posts list.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This site is unfinished. [storage world](index.html)

