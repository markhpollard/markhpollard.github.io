---
title: Articles
layout: archive
permalink: "/strategy-articles"
h1: Strategy Articles
---

<main class="preview" id="all-container">
  {% for post in site.posts %}
        <a href="{{ site.github.url }}{{ post.url }}">
        <div class="object">
            <div class="year">{{ post.pubdate }}</div>
            <div class="project">{{ post.title }}</div>
            <div class="type">{{ post.tags }}</div>
            <div class="publication">{{ post.publication }}</div>
        </div>
    </a>

    {% endfor %}

</main>

<section class="clear"></section>


