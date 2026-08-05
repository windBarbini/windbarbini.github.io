---
layout: page
title: "GIS"
permalink: /gis/
main_nav: true
nav_order: 2
---

{% assign gis_posts = site.categories.gis %}

<ul class="posts-list">
{% for post in gis_posts %}
    <li>
        <strong>
            <a href="{{ post.url | prepend: site.baseurl }}">
                {{ post.title }}
            </a>
        </strong>
        <span class="post-date">- {{ post.date | date_to_long_string }}</span>
    </li>
{% endfor %}
</ul>
