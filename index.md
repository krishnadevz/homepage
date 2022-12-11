---
layout: default
---

# Hello!

I'm Brian, a software devleoper and educator living in Boston, Massachusetts.
I graduated from Harvard College in 2019 with a degree in computer science and linguistics
and from Harvard Graduate School of Education in 2021 with a master's degree in technology, innovation, and education.

I run [Spanning Tree](https://youtube.com/spanningtree), a video series teaching topics in computer science and mathematics. I've taught at [Harvard University](https://harvard.edu), where I created courses focusing on [artificial intelligence](https://edx.org/course/cs50s-introduction-to-artificial-intelligence-with-python)
and [web programming](https://edx.org/course/cs50s-web-programming-with-python-and-javascript).
I have also been a course head for [CS50](https://cs50.harvard.edu/), Harvard's introductory course in computer science, and a co-instructor for [CS51](https://cs51.io/), Harvard's course on abstraction and design in computing.

I currently work at [Byteboard](https://byteboard.dev), developing a more accurate and equitable process for engineering hiring. I've worked previously at [Automattic](https://automattic.com), [Palantir](https://palantir.com), and the [National Speech and Debate Association](https://speechanddebate.org).

Contact me at <brian@brianyu.me>.

## Projects

{% for project in site.data.projects %}
{% if project.category == "project" %}
{% include project.html project=project %}
{% endif %}
{% endfor %}

See [my GitHub profile](http://github.com/brianyu28) for other projects I've created or worked on.
