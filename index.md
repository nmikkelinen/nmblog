---
layout: default
title: "Welcome to the Log"
css: style-test.css
---
<h1>Welcome to the Log</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

<h2>About this space</h2>
<p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>

<h2>Log Entries</h2>

<div id="filter-info">Filtering by: <span id="active-tag" style="color:#e2e8f0;font-weight:600;"></span> <a href="/index.html">(Show all)</a></div>

<ul class="posts" style="list-style:none;padding:0;margin:0;">
{% for post in site.posts %}
    <li class="post-item" data-tag="{{ post.tags }}" style="margin-bottom:24px;">
        <strong>{{ post.date | date: "%Y-%m-%d" }}</strong> | <a href="{{ post.url }}">{{ post.title }}</a>  
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
