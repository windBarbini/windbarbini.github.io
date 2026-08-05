---
layout: page
title: "Art"
permalink: /art/
main_nav: true
nav_order: 5
---

# This is where I'll put my cross-stitch and pattern generators

{% assign art_posts = site.categories.art %}

{% for tag in site.tags %}
  {% assign tag_name = tag | first %}
  {% assign tag_posts = tag | last %}

  {% assign has_art_posts = false %}
  {% for post in tag_posts %}
    {% if post.categories contains "art" or post.categories contains "art" %}
      {% assign has_art_posts = true %}
    {% endif %}
  {% endfor %}

  {% if has_art_posts %}
    <h2>{{ tag_name | capitalize }}</h2>

    <ul class="posts-list">
    {% for post in tag_posts %}
      {% if post.categories contains "art" or post.categories contains "art" %}
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