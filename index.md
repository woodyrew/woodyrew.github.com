---
published: true
layout: page
title: Javascript based development.
tagline: "Thing's I've found useful."
---

{% include JB/setup %}

This blog is really just a quick way for me to keep track of the useful things I come across and hopefully pass on some wisdom to others.

## Things I'll be covering

 - General JavaScript
 - AngularJS
 - Node.js
 - MongoDB
 - Bash CLI

Enjoy, and if you have any comments let me know via twitter or github.

## Posts
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{post.date | date_to_string}}</span> &raquo; <a href="{{BASE_PATH}}{{post.url}}">{{post.title}}</a></li>
  {% endfor %}
</ul>

Installed from: [Jekyll Bootstrap](http://jekyllbootstrap.com)
