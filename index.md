---
layout: page
title: Binary Farts
tagline: Ruminations of a Techie
---

Hey there,

This blog here is my attempt at writing about technology, even though I don't know much--I'll use it as an excuse to learn stuff and write about it(I love to write). Hopefully, I'll keep updating it more frequently than my other <a href="http://paradoxadinfinitum.wordpress.com/">blog</a>(that one is me bitching about stuff).

## Latest Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Ways to tell me to shut up!!

If you ever feel the need to tell me to take a jump off a friggin' cliff(or maybe just to say hi) or to contact me related to stuff(tech or non-tech), following are the ways to do so:

<ul class="contact-details">
<li><a href="https://www.facebook.com/CreedSama">Facebook</a></li>
<li><a href="https://twitter.com/Creedsama">Twitter</a></li>
<li>Emails: <a href="mailto:vakul.m.arora@gmail.com">This</a> or <a href="mailto:bourne.snake@gmail.com">this</a></li>
</ul>