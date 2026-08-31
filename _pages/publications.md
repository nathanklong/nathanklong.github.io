---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

## Publications

<input type="text"
       class="pub-search"
       id="pubSearch"
       placeholder="Filter by title, author, or year..."
       autocomplete="off">

<div class="section-card" id="pubList">
<h3>Preprints</h3>

{% bibliography --query @unpublished %}

<h3>Book Chapters</h3>

{% bibliography --query @incollection %}

<h3>Journal Articles</h3>

{% bibliography --query @article %}

<h3>Conference Proceedings</h3>

{% bibliography --query @inproceedings %}

<h3>Theses</h3>

{% bibliography --query @mastersthesis @phdthesis %}
</div>
