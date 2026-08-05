---
layout: page
title: "Art"
permalink: /art/
main_nav: true
nav_order: 5
---

# This is where I'll put my cross-stitch and pattern generators

{% assign allowed_categories = "art" | split: "," %}

{% for category in site.categories %}
  {% capture cat %}{{ category | first }}{% endcapture %}
  {% if allowed_categories contains cat %}
  <h2 id="{{cat}}">{{ cat | capitalize }}</h2>
  {% for desc in site.descriptions %}
    {% if desc.cat == cat %}
      <p class="desc"><em>{{ desc.desc }}</em></p>
    {% endif %}
  {% endfor %}
  <ul class="posts-list">
  {% for post in site.categories[cat] %}
    <li>
      <strong>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </strong>
      <span class="post-date">- {{ post.date | date_to_long_string }}</span>
    </li>
  {% endfor %}
  </ul>
  {% if forloop.last == false %}<hr>{% endif %}
{% endfor %}
<br>