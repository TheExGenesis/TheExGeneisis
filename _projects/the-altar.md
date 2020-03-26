---
short_name: altar
title: "The Altar"
---

Where the offerings to the gods of the internet are gathered. Every week I curate and post a selection of 5 links to obscure things I find and appreciate. These have been serving the dual purpose of painting a picture about who I am aesthetically (not necessarily visually) - and getting me into the habit of posting and tending to this blog.

as part of my weekly reviews I'll be posting 5 links of things I find every week with brief explainers of why I like them. This way, you can benefit from my useless scouring of the web, and I can signal my eclectic taste

<ul>
  {% for post in site.categories.offerings %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>