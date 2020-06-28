---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
title: ''
excerpt: "One Stop for financial information including taxation, accounting and a lot more. Please check our [`blog`](/blog) for latest articles"
header:
  overlay_image: /assets/images/FB_IMG_Logo.jpg
  overlay_filter: 0
---

<h1>Recent Posts</h1>
<div class="recent__posts">
{% for post in site.posts limit:3 %}
  {% include card.html post=post %}
{% endfor %}
</div>
