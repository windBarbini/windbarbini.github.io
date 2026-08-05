---
layout: page
title: "GIS"
permalink: /gis/
main_nav: true
nav_order: 2
---

{% assign gis_posts = site.categories.gis %}

{% for tag in site.tags %}
{% assign tag_name = tag | first %}
{% assign tag_posts = tag | last %}
{% assign has_gis_posts = false %}

{% for post in tag_posts %}
{% if post.categories contains "gis" or post.categories contains "gis" %}
{% assign has_gis_posts = true %}
{% endif %}
{% endfor %}

{% if has_gis_posts %}
<h2 class="tag-header">{{ tag_name | capitalize }}</h2>

<ul class="posts-list">
{% for post in tag_posts %}
{% if post.categories contains "gis" or post.categories contains "gis" %}
<li>
<strong>
<a href="{{ post.url | prepend: site.baseurl }}">
{{ post.title }}
</a>
</strong>
<span class="post-date">- {{ post.date | date_to_long_string }}</span>
</li>
{% endif %}
{% endfor %}
</ul>

{% endif %}
{% endfor %}

<style>
.gis-tag-header {
  margin-top: 1em;
  margin-bottom: 0.25em;
}

.gis-tag-header + .posts-list {
  margin-top: 0;
}
</style>