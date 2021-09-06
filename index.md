---
layout: default
---

# Hello!

I'm Brian, a Software Engineer at [Automattic](https://automattic.com).
I graduated from Harvard College in 2019 with a degree in computer science and linguistics
and from Harvard Graduate School of Education in 2021 with a master's degree in technology, innovation, and education.

Before joining Automattic, I worked at Harvard as a Senior Preceptor in computer science,
where I created courses focusing on [artificial intelligence](https://www.edx.org/course/cs50s-introduction-to-artificial-intelligence-with-python)
and [web programming](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript),
and where I was a course head for [CS50](https://cs50.harvard.edu/), Harvard's introductory course in computer science.
I've also worked previously at [Palantir](https://www.palantir.com) and the [National Speech and Debate Association](https://www.speechanddebate.org).

Contact me at <brian@brianyu.me>.

## Spanning Tree

When I'm not working, I run [Spanning Tree](https://spanningtree.me/), a collection of animated videos on topics in computer science and mathematics on [YouTube](https://www.youtube.com/spanningtree).

<script src="https://apis.google.com/js/platform.js"></script>
<div class="g-ytsubscribe" data-channelid="UCDzVUXiTr3hClI-zzCWbYzg" data-layout="default" data-count="default"></div>

<div class="embed"><iframe src="https://www.youtube.com/embed/videoseries?list=PLZErML25eQ-NK9uR6Jw-NKrA_PlsB78b_" frameborder="0" allowfullscreen></iframe></div>

<div class="embed"><iframe src="https://spanningtree.substack.com/embed" style="border:1px solid #EEE; background:white" frameborder="0" scrolling="no"></iframe></div>

## Posts

{% for post in site.posts limit:5 %}
{% include preview.md post=post %}
{% endfor %}

<a class="pure-button" href="/posts">View all posts</a>
