---
title: "First Post!"
comments: true
header:
  teaser: /assets/images/post/2020-04-25-first-post/Untitled-1.png
  overlay_image: /assets/images/post/2020-04-25-first-post/Untitled-1.png
last_modified_at: 2020-04-25
categories:
  - Blog
tags:
  - Untagged
---

This is the first blog post on this website!

In this blog section,  I'll be posting stuff mostly about 3D printing. On this site, I'll put anything that I find cool. I'll be posting something when I get something cool to post.

My favourite colour is green, specifically, 

<p style="color:#0dbf1f">this green here (#0dbf1f).</p>



{% capture fig_img %}
[![Foo]({{ '/assets/images/post/2020-04-25-first-post/portrait.png' | relative_url}})](https://jacobtian.com/asdasdasd/)
{% endcapture %}

{% capture fig_caption %}
A picture of myself walking down a path
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>