---
layout: page
title: Age of Empires Port for iOS
tagline: By Dan Malone
---

## About me

Hey guys, I'm a Fourth year Computer Science student in DCU.

I'm aiming to create an iOS port of Age of Empires - Crazy huge I know its unlikely to hit full scope but theres something alluring about attacking a huge project.

My reasoning behind remaking this game is: I want to justify mobile as a decent platform for modern gaming, RTS and RPGs are ideal for this platform but console and PC is still the main platform. I decided that using a game that is already considered great and adapting it to work well for mobile is the best way to justify the platform, HCI is everything.

## Posts

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
