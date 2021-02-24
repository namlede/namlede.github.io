---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Home
---

![me](/assets/guitar.jpg)
{: id="headshot"}

I'm a third year PhD student in Harvard's [Theory of Computation](https://toc.seas.harvard.edu/) and [ML Theory](https://mltheory.org/) groups. I'm advised by [Leslie Valiant](http://people.seas.harvard.edu/~valiant/) and supported by an NSF Graduate Research Fellowship. Previously, I undergraduated in math at Princeton.

I'm interested in theoretical computer science broadly. In particular, I study the interplay between algorithms, learning, and strategic behavior.

<small> bedelman@g.harvard.edu | [Google Scholar](https://scholar.google.com/citations?user=mQSj2C0AAAAJ&hl=en) | he/him </small>


## News
[Chara Podimata](https://www.charapodimata.com/), [Yo Shavit](https://yonadavshavit.com/), and I are organizing a tutorial at [FAccT 2021](https://facctconference.org/2021/acceptedtuts.html) called **[How to Achieve Both Transparency and Accuracy in Predictive Decision Making: An Introduction to Strategic Prediction](tutorial.html)**!

## Publications
{% for item in site.data.pubs %}
**[{{ item.title }}]({{ item.link }})** <br>
with {{ item.coauthors }} <br>
*{{ item.venue }}*
{% endfor %}

## Miscellaneae

- [Undergraduate Senior Thesis](/assets/thesis.pdf)
- [Guest blog post on quantum Hamiltonian complexity](https://windowsontheory.org/2018/12/20/quantum-hamiltonian-complexity/)
- [Quantum money for knot theorists](/assets/money.pdf)