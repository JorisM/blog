---
layout: page
title: Blog
tagline: Neuigkeite, Tips und Tricks
---
{% include JB/setup %}
<dl class="posts">
  {% for post in site.posts %}
    <dt><span>{{ post.date | date_to_string }}</span></dt>
	<dd><a href="{{ BASE_PATH }}/blog/{{ post.url }}">{{ post.title }}</a></dd>
  {% endfor %}
</dl>


