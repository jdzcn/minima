---
layout: default
title: Linux
permalink: /linux/
---

<ul>
  {% for post in site.posts %}
	{% if post.tags contains 'linux' %}
		<li>
		      <a href="{{ post.url }}">{{ post.title }}</a>
		      
		</li>
	{% endif %} 
  {% endfor %}
</ul>