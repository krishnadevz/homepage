---
layout: default
num_excerpts: 5
---

<h1 style="text-align:center">Posts</h1>

{% for post in site.posts limit:page.num_excerpts %}
{% include preview.md post=post %}
{% endfor %}

{% if site.posts.size > page.num_excerpts %}

## Older Posts

<ul>
    {% for post in site.posts offset:page.num_excerpts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

{% endif %}