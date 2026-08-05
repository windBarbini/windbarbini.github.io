---
layout: page
title: "Art"
permalink: /art/
main_nav: true
nav_order: 5
---

# This is where I'll put my cross-stitch and pattern generators

{% for tag in site.tags %}
  {% capture tag_name %}{{ tag | first }}{% endcapture %}

  <h2 id="{{ tag_name }}">{{ tag_name | capitalize }}</h2>

  <ul class="posts-list">
  {% for post in site.tags[tag_name] %}
    {% if post.categories contains "art" %}
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

  {% unless forloop.last %}<hr>{% endunless %}
{% endfor %}