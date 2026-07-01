---
layout: null
title: "Lorem Ipsum Article Three"
description: "A third test entry sitting in the middle to verify the pagination layout with both previous and next links."
tags: "NIS2"
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

# {{ page.title }}

*Published on June 28, 2026*

## Testing the Middle Post
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<hr><footer>{% if page.previous %}<a href="{{ page.previous.url }}">&lt;&lt; Previous</a>{% else %}<a href="#" class="disabled">&lt;&lt; Previous</a>{% endif %}<a href="/index.html">Home</a>{% if page.next %}<a href="{{ page.next.url }}">Next &gt;&gt;</a>{% else %}<a href="#" class="disabled">Next &gt;&gt;</a>{% endif %}</footer>
