---
title: Articles
permalink: /strategy-articles/
summary: How do you do planning? What’s an insight? Where do ideas come from? Who
  am I? Words here.
categories: strategy articles, strategy article, articles on strategy
h1: Strategy Articles
layout: archive
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


