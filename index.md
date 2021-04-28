---
layout: default
---

# Hello!

I'm Brian, a Senior Preceptor at Harvard's [Division of Continuing Education](https://www.dce.harvard.edu).
I graduated from Harvard College in 2019 with a degree in computer science and linguistics.
I currently teach [Introduction to Artificial Intelligence with Python](http://cs50.edx.org/ai) and [Web Programming with Python and JavaScript](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript), offered through edX, Harvard Extension School and Harvard Summer School.
I work with the team at [CS50](https://cs50.harvard.edu/), Harvard's introductory course in computer science, where I focus on teaching, curricular development, outreach, and software tools.

I have previously worked with a number of other computer science classes, including CS51, Harvard's course on abstraction and design in computing and CS124, Harvard's introduction to algorithms. I've worked previously at [Palantir](https://www.palantir.com), [The Harvard Crimson](https://www.thecrimson.com), [3P Speech](https://www.3pspeech.com), and the [National Speech and Debate Association](https://www.speechanddebate.org).

Contact me at <brian@brianyu.me>.

## Spanning Tree

When I'm not working, I run [Spanning Tree](https://spanningtree.me/), a collection of animated videos on topics in computer science and mathematics on [YouTube](https://www.youtube.com/spanningtree).

<script src="https://apis.google.com/js/platform.js"></script>
<div class="g-ytsubscribe" data-channelid="UCDzVUXiTr3hClI-zzCWbYzg" data-layout="default" data-count="default"></div>
{% include youtube.html title="Dominos" url="https://www.youtube.com/embed/w6E7aQnA4Ws" %}

<!--
<div class="embed"><iframe src="https://www.youtube.com/embed/videoseries?list=PLZErML25eQ-NK9uR6Jw-NKrA_PlsB78b_" frameborder="0" allowfullscreen></iframe></div>
-->

[Sign up](https://spanningtree.substack.com) to receive email updates whenever a new video is published.

<!--
<div class="embed"><iframe src="https://spanningtree.substack.com/embed" style="border:1px solid #EEE; background:white" frameborder="0" scrolling="no"></iframe></div>
-->

## Posts

{% for post in site.posts limit:5 %}
{% include preview.md post=post %}
{% endfor %}

<a class="pure-button" href="/posts">View all posts</a>
