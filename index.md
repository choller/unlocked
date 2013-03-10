---
layout: front
title: (Un)locked
description: Lock picking, physical security and new bypass methods
---
{% include JB/setup %}

<div class="span6">
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
	{{ post.content | more: "excerpt" }}
          <p><a class="btn" href="{{ BASE_PATH }}{{ post.url }}">More »</a></p>
   </li>
  {% endfor %}
</ul>
</div>

<div class="span6">
  <h3>Contact</h3>
  <!--{{ page.contact }}-->
  <p><a class="btn" href="/contact/#email">Email »</a></p>
</div>
