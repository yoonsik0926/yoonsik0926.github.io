---
layout: page
title: Kotlin
permalink: /blog/categories/Kotlin/
---

<h5> Posts by Category : {{ page.title }} </h5> 

<div class="card">
{% for post in site.categories.Kotlin %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>
