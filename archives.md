---
layout: post
title: "Archives"
date:   2014-05-13 09:45:16
categories: general
permalink: /archives/
---

<div class="posts">
  <ul class="posts-list">
	{% for post in site.posts %}
	  <li class="post-link">
		<a class="post-title" href="{{ post.url }}">
		  <span class="post-date">{{ post.date | date_to_string }}</span> :: 
		  {{ post.title }}
		</a>
	  </li>
	{% endfor %}
  </ul>
</div>
