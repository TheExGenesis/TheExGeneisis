---
layout: page
title: Blog
navlevel: header
navtitle: Blog # optional, specifies the text to display on navigation item
position: 2
---

Welcome to _the blog_™. 

I don't really like the term _blogchain_ but I've been accumulating weekly sets of 5 amazing, usually obscure links. I refer to them as "offerings" and keep them all in [~The Altar~](_projects/the-altar.md)

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>