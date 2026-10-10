---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<style>
  .publications .author em {
    color: var(--global-theme-color, #b509ac);
    font-style: normal;
    font-weight: 700;
  }
</style>

<p style="padding: 0.75rem 1rem; border-left: 3px solid var(--global-theme-color, #b509ac); background-color: rgba(181, 9, 172, 0.08); border-radius: 0.25rem;">
  I have <strong style="color: var(--global-theme-color, #b509ac); font-weight: 700;">three additional papers in progress</strong>. You can learn more about them on the <a href="{{ '/projects/' | relative_url }}">Projects</a> page.
</p>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
