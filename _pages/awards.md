---
layout: page
title: "Awards"
permalink: /awards/
---

<style>
.cards {display:grid; grid-template-columns: repeat(auto-fill,minmax(260px,1fr)); gap:16px; margin-top: 1rem;}
.card {border:1px solid #e5e7eb; border-radius:16px; overflow:hidden; background:#fff; box-shadow:0 2px 8px rgba(0,0,0,.04); transition:transform .15s ease, box-shadow .15s ease;}
.card:hover {transform:translateY(-2px); box-shadow:0 6px 16px rgba(0,0,0,.08);}
.card-link {text-decoration:none; color:inherit; display:block;}
.card-thumb {width:100%; aspect-ratio:16/9; object-fit:cover; display:block; background:#f6f7f9;}
.card-body {padding:14px 16px;}
.card-date {font-size:.875rem; color:#6b7280;}
.card-title {margin:6px 0 6px; font-size:1.0rem; line-height:1.4;}
.card-excerpt {margin:0; color:#374151; font-size:.95rem;}
</style>

<div class="cards">
{%- assign awards = site.posts | where_exp: "p", "p.categories contains 'awards'" -%}
{%- for post in awards -%}
  {%- assign thumb = post.image | default: '/images/awards_default.jpg' -%}
  <article class="card">
    <a class="card-link" href="{{ post.url | relative_url }}">
      <img class="card-thumb" src="{{ thumb | relative_url }}" alt="">
      <div class="card-body">
        <time class="card-date">{{ post.date | date: "%Y-%m-%d" }}</time>
        <h3 class="card-title">{{ post.title }}</h3>
        {%- if post.excerpt -%}
          <p class="card-excerpt">{{ post.excerpt | strip_html | truncate: 140 }}</p>
        {%- endif -%}
      </div>
    </a>
  </article>
{%- endfor -%}
</div>
