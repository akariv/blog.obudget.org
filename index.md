---
layout: page
title: בלוג מפתח התקציב
tagline: פוסטים אחרונים
---


<ul>
  {% for post in site.posts %}
    <li>
	<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
	<p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
