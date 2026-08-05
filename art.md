---
layout: page
title: "Art"
permalink: /art/
main_nav: true
nav_order: 5
---

# This is where I'll put my cross-stitch and pattern generators
{% assign art_posts = site.categories.art | sort: "order" %}

<ul class="posts-list">
{% for post in art_posts %}
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
