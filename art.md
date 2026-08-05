---
layout: page
title: "Art"
permalink: /art/
main_nav: true
nav_order: 5
---

# This is where I'll put my cross-stitch and pattern generators
{% assign tutorials = site.art | sort: "order" %}

<ul class="posts-list">
{% for tutorial in tutorials %}
    <li>
        <a href="{{ tutorial.url | prepend: site.baseurl }}">
            {{ tutorial.title }}
        </a>
    </li>
{% endfor %}
</ul>

