---
layout: default
title: Home
---

![me](/assets/headshot.jpg)
{: id="headshot"}



I'm a final-year PhD student in Harvard's [Machine Learning Foundations](https://mlfoundations.org/) and [Theory of Computation](https://toc.seas.harvard.edu/) groups. I'm advised by [Sham Kakade](https://sham.seas.harvard.edu/) and [Leslie Valiant](http://people.seas.harvard.edu/~valiant/). Previously, I undergraduated in math at Princeton. In summer 2021, I interned with the ML group at Microsoft Research NYC, where I had the pleasure of working with [Cyril Zhang](https://cyrilzhang.com/) and [Surbhi Goel](https://www.surbhigoel.com). 

My research, which is currently focused on the scientific study of deep learning, is motivated by the following claims:
- If we understand AI systems better, we will have a better shot at making them safer and foreseeing future technological developments.
- It is crucial to build understanding of cutting-edge methods, and for our insights to generalize across changes in algorithms and scale.
- The shortest path to scientific understanding involves a blend of both theory and empirics, on both clean toy models and real messy systems.

In the past, I've also worked on game theory and computational complexity theory.

<small> bedelman@g.harvard.edu | [Google Scholar](https://scholar.google.com/citations?user=mQSj2C0AAAAJ&hl=en) </small>

## Research
**[The Evolution of Statistical Induction Heads: In-Context Learning Markov Chains](https://arxiv.org/abs/2402.11004)** <br>
with Ezra Edelman, Surbhi Goel, Eran Malach, and Nikolaos Tsilivis <br>
*preprint* | [Blog post](https://unprovenalgos.github.io/statistical-induction-heads)


**[Distinguishing the Knowable from the Unknowable with Language Models](https://arxiv.org/abs/2402.03563)** <br>
with Gustaf Ahdritz, Tian Qin, Nikhil Vyas, and Boaz Barak <br>
*preprint*

**[Watermarks in the Sand: Impossibility of Strong Watermarking for Generative Models](https://arxiv.org/abs/2311.04378)** <br>
with Hanlin Zhang, Danilo Francati, Daniele Venturi, Giuseppe Ateniese, and Boaz Barak <br>
Secure and Trustworthy LLMs Workshop @ ICLR 2024 | [Blog post](https://www.harvard.edu/kempner-institute/2023/11/09/watermarking-in-the-sand/)

**[Feature emergence via margin maximization: case studies in algebraic tasks](https://arxiv.org/abs/2311.07568)** <br>
with Depen Morwani, Costin-Andrei Oncescu, Rosie Zhao, and Sham Kakade <br>
*ICLR 2024 (spotlight)* | [Blog post](https://www.harvard.edu/kempner-institute/2023/11/14/where-do-features-come-from-a-story-of-sinusoids-and-inductive-biases/)

{% for item in site.data.pubs %}
**[{{ item.title }}]({{ item.link }})** <br>
with {{ item.coauthors }} <br>
*{{ item.venue }}*
{% endfor %}

## Teaching
<span>Spring 2021</span>{: class="date-brackets"} Teaching fellow for **CS 229br: Biology and Complexity** <br>
 Received Certificate of Distinction in Teaching from Harvard University

<span>Spring 2020</span>{: class="date-brackets"} Teaching fellow for **CS 228: Computational Learning Theory** <br>
Gave three lectures on "Mysteries of Generalization in Deep Learning"

## Tutorials
**[How to Achieve Both Transparency and Accuracy in Predictive Decision Making: An Introduction to Strategic Prediction](tutorial.html)** <br>
with Chara Podimata and Yonadav Shavit <br>
*FAccT 2021*

## Recent talks
<span>January 2024</span>{: class="date-brackets"} Watermarks in the Sand: Impossibility of Strong Watermarking for Generative Models <br>
[NYC Crypto Day](https://nycryptoday.wordpress.com/)


<span>February 2023</span>{: class="date-brackets"} [Studies in feature learning through the lens of sparse boolean functions](https://mpml.tecnico.ulisboa.pt/seminars?id=6910) <br>
Seminar in Mathematics, Physics and Machine Learning, University of Lisbon

<span>November 2022</span>{: class="date-brackets"} Hidden progress in deep learning <br>
[Statistical Learning Theory and Applications](https://cbmm.mit.edu/9-520/syllabus), MIT course

<span>September 2022</span>{: class="date-brackets"} Sparse feature emergence in deep learning <br>
Alg-ml seminar, Princeton University

<span>May 2022</span>{: class="date-brackets"} Towards demystifying the inductive bias of attention mechanisms <br>
[Collaboration on the Theoretical Foundations of Deep Learning](https://deepfoundations.ai)

<span>Feb 2022</span>{: class="date-brackets"} [Towards demystifying transformers & attention](https://cmsa.fas.harvard.edu/event/2-9-2022-new-technologies-in-mathematics-seminar/) <br>
New Technologies in Mathematics Seminar, Harvard Center of Mathematical Sciences and Applications

## Miscellaneae
- [AI will change the world, but won’t take it over by playing "3-dimensional chess"](https://windowsontheory.org/2022/11/22/ai-will-change-the-world-but-wont-take-it-over-by-playing-3-dimensional-chess/), blog post with Boaz Barak
- [Undergraduate Senior Thesis](/assets/thesis.pdf) on arithmetic circuit complexity
- Expositions of [quantum Hamiltonian complexity](https://windowsontheory.org/2018/12/20/quantum-hamiltonian-complexity/) and [quantum money for knot theorists](/assets/money.pdf)