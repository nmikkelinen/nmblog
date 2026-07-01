---
layout: null
---
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="/style.css?v=4">

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

<div id="filter-info">Filtering by: <span id="active-tag" style="color:#e2e8f0;font-weight:600;"></span> <a href="#">(Show all)</a></div>

<ul class="posts">
{% for post in site.posts %}
    <li class="post-item" data-tag="{{ post.tags }}">
        **{{ post.date | date: "%Y-%m-%d" }}** — [{{ post.title }}]({{ post.url }})  
        <div style="margin-top:4px;">{{ post.description }}</div>
        <div class="tag-box">
            <a href="#{{ post.tags }}" class="tag">{{ post.tags }}</a>
        </div>
    </li>
{% endfor %}
</ul>

<script>
function filterPosts() {
    const hash = decodeURIComponent(window.location.hash.substring(1)).trim();
    const items = document.querySelectorAll('.post-item');
    const info = document.getElementById('filter-info');
    const activeTagSpan = document.getElementById('active-tag');

    if (hash) {
        items.forEach(item => {
            const itemTag = item.getAttribute('data-tag').trim();
            item.style.display = (itemTag === hash) ? 'block' : 'none';
        });
        activeTagSpan.textContent = hash;
        info.style.display = 'block';
    } else {
        items.forEach(item => item.style.display = 'block');
        info.style.display = 'none';
    }
}
window.addEventListener('hashchange', filterPosts);
window.addEventListener('DOMContentLoaded', filterPosts);
</script>
