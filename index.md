---
layout: home
---

# Growth Mindset Journal

One purpose: to help me achieve my long term goals.

The creation of this repository was heavily influenced by my favorite teacher who also made a website for reflections and reflected consistently. Her way of teaching, learning, and discipline moved me greatly, and so here I am, with my own reflection website.

## Recent Reflections
{% for post in site.posts %}
- **{{ post.date | date: "%b %d, %Y" }}**: [{{ post.title }}]({{ post.url }})
{% endfor %}

[View my long-term goals →](/goals)
