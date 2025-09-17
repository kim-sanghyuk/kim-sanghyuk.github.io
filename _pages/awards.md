---
layout: page
title: "Awards"
permalink: /awards/
---

<ul class="post-list">
  {%- assign awards = site.posts | where_exp: "p", "p.categories contains 'awards'" -%}
  {%- for post in awards -%}
    <li>
      <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
      <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a>
      {%- if post.excerpt -%}
        <p>{{ post.excerpt | strip_html | truncate: 140 }}</p>
      {%- endif -%}
    </li>
  {%- endfor -%}
</ul>
