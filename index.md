---
layout: default
title: Home
---

Welcome to **Discrete Mathematics** — notes and worked solutions.
All math is LaTeX via MathJax, e.g. \( \sum_{k=0}^n \binom{n}{k} = 2^n \).

### Notes
<ul class="clean">
{%- assign ns = site.notes | sort: 'title' -%}
{%- for n in ns -%}
  <li><a href="{{ n.url | relative_url | prepend: site.baseurl }}">{{ n.title }}</a></li>
{%- endfor -%}
</ul>

### Solutions
<ul class="clean">
{%- assign ss = site.solutions | sort: 'title' -%}
{%- for s in ss -%}
  <li><a href="{{ s.url | relative_url | prepend: site.baseurl }}">{{ s.title }}</a></li>
{%- endfor -%}
</ul>
