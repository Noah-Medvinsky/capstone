---
title: Developer’s Perspective
permalink: /developers-perspective/
---

# Developer’s Perspective

<p class="lead">How the project was put together, from the raw ChIP-seq data to the final comparison. The themes build on each other, so reading them in order tells the full story. Each theme shows the artifacts of that part of the work and how it changed over the quarter.</p>

{% assign dev = site.data.nav | where: "url", "/developers-perspective/" | first %}
<ol class="theme-list">
  {%- for t in dev.children %}
  <li><a href="{{ t.url | relative_url }}">
    <span class="num">{{ forloop.index }}</span>
    <span><strong>{{ t.title }}</strong><span class="blurb">{{ t.blurb }}</span></span>
  </a></li>
  {%- endfor %}
</ol>
