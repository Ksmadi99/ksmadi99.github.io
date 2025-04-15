---
layout: page
title: Knowledge Hub
permalink: /knowledge/
---

# Knowledge Hub

**Tech Support & Beyond: Knowledge, Services, Security**  
As an IT Support Executive with over 1 year of experience, I share practical guides to help you navigate the IT world. Explore my tips and tricks below, and [contact me](/contact/) if you need personalized support!

{% for post in site.posts %}
  <div class="post-item">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
    <p>{{ post.excerpt }}</p>
    <a href="{{ post.url }}" class="read-more">Read More</a>
  </div>
{% endfor %}
