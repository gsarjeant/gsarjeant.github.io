---
layout: base
---
## I'm Greg Sarjeant

I am a human on the Internet.

These are things I have written most recently.
    
{% for post in site.posts limit:5 %}
  [{{ post.title }}]({{ post.url }})
{% endfor %}
