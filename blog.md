---
layout: page
title: Blog
---

# 📰 Blog Archive

All blog posts are listed below.

---

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
📅 {{ post.date | date: "%B %d, %Y" }}  
🏷️ {{ post.tags | join: ", " }}

{{ post.excerpt }}

---
{% endfor %}

⬅️ Back to [Home](/)
