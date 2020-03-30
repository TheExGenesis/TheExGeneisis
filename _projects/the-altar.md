---
short_name: altar
title: "The Altar"
---

![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxiqo%2FRJoN6ky1W9?alt=media&token=c46303e6-b703-4cee-ad04-e158b55b590d)

Where the offerings to the gods of the internet are gathered. Every week I curate and post a selection of 5 links to obscure things I find and appreciate. These have been serving the dual purpose of painting a picture about who I am aesthetically (not necessarily visually) - and getting me into the habit of posting and tending to this blog.


If you'd like offerings to be delivered directly to your (digital) doorstep, you can sign up to my mailing list. You'll get exactly 1 email every Sunday with the treasures I find. 

{% include mailing-signup.html %}


# The offerings:

<ul>
  {% for post in site.categories.offerings %}
    &emsp;<li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>