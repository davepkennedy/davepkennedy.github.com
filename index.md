---
layout: default
title: davepkennedy
subsection: Hello
---
I should probably fill this thing in…

### Stuffs

<ul class="posts">
{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}/{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
