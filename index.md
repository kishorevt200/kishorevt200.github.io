---
layout: home
title: Home
---

# 👋 Welcome to My Blog

Hi, I'm **twh4t**.  
I write about programming, learning, and projects.

---

## 📝 Latest Posts

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url }})
📅 {{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

---
{% endfor %}

➡️ **Read all posts:** [View Blog](blog.md)
