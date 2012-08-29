---
layout: page
title: Binary Farts
tagline: Ruminations of a Techie
---

Hey there,

Oh, sorry, I forgot to introduce myself. My name is Vakul. I am a fledgling programmer trying to find his way in this big confusing maze called 'The World of Code'. I know a bit of Java, PHP, C, The .NET Framework(most of the stuff that I learnt in College); workable knowledge in Mobile Apps--Android and Cross-platform apps made using the PhoneGap framework. Lately, I have been messing with Python, Ruby(mixed in with Rails), and some other technologies. Suffice to say, that I'm having a lot of fun while learning.

But this was not the case before. Back in college, I was not at all interested in coding...I mean I was, but I was also in a very depressed state of mind. That lead to me being apathetic towards everything I enjoyed. Life became a drag; everything came to a stop for me. I won't go into the details, for that is not the purpose of this blog. 

The reason I started this blog--well, Github has this awesome free service where you could host your own pages, and I had read up on Jekyll(Ruby gem) made specifically for this purpose, so I thought, 'Why not?'
Also, I wanted to start a tech blog, so...

Anyway, I will be filling this blog up with stuff related to code and stuff I learn about.  

As you can see, I love to write. I have another <a href="http://paradoxadinfinitum.wordpress.com/">blog</a> where I write about random stuff and at times short stories. If you ever have free time, do check it out.

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