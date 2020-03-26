---
short_name: altar
title: "The Altar"
---

Where the offerings to the gods of the internet are gathered. Every week I curate and post a selection of 5 links to obscure things I find and appreciate. These have been serving the dual purpose of painting a picture about who I am aesthetically (not necessarily visually) - and getting me into the habit of posting and tending to this blog.


# The offerings:

<ul>
  {% for post in site.categories.offerings %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>