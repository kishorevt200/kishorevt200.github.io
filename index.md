---
layout: home
title: "YourName's Writeups"
---

# 🔐 CTF & Security Writeups

Welcome to my writeup archive.

## Latest Posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
