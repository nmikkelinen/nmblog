---
layout: null
---
<link rel="stylesheet" href="/style.css?v=2">

<header>
    <nav>
        <a href="/index.html">Home</a>
        <a href="/templates.html">Templates</a>
        <a href="/cv.html">CV</a>
    </nav>
</header>
<hr>

# Welcome to the Log

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

## About this space

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

## Log Entries

{% for post in site.posts %}
* **{{ post.date | date: "%Y-%m-%d" }}** — [{{ post.title }}]({{ post.url }}) <span style="color: #64748b; font-size: 0.85rem; margin-left: 6px; font-weight: 500;">#{{ post.tags }}</span>  
    {{ post.description }}
{% endfor %}
