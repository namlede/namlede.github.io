---
layout: default
title: Home
---

![me](/assets/headshot.jpg)
{: id="headshot"}

I founded and lead the Agent Security team at the [Center for AI Standards and Innovation](https://www.nist.gov/caisi/) (CAISI), a hub of AI expertise in the U.S. government. Our team does research, evaluations, red teaming, and standards development to measure and improve the security of advanced AI systems.

Some things we've been up to:	
- [agent hijacking evaluations](https://www.nist.gov/news-events/news/2025/01/technical-blog-strengthening-ai-agent-hijacking-evaluations)
- finding vulnerabilities and exploits for a [variety](https://openai.com/index/us-caisi-uk-aisi-ai-update/) of [AI systems](https://www.anthropic.com/news/strengthening-our-safeguards-through-collaboration-with-us-caisi-and-uk-aisi)
- studying what happens when models [cheat on agent evals](https://www.nist.gov/caisi/cheating-ai-agent-evaluations)
- [request for information](https://www.nist.gov/news-events/news/2026/01/caisi-issues-request-information-about-securing-ai-agent-systems) on agent security
	
I live in Princeton, NJ, where I am a Princeton University [AI Lab](https://ai.princeton.edu/ai-lab) Policy Fellow. I joined government in 2024 as a [TechCongress](https://techcongress.io/) AI Security Fellow after my PhD.

During my PhD in Computer Science at Harvard, I co-founded the [ML Foundations](https://mlfoundations.org/) research group and was supported by a NSF Graduate Research Fellowship. My advisors were [Sham Kakade](https://shamulent.github.io/) and [Leslie Valiant](https://people.seas.harvard.edu/~valiant/); I was also privileged to have [Boaz Barak](https://www.boazbarak.org/), [Cyril Zhang](https://cyrilzhang.com/), and [Surbhi Goel](https://www.surbhigoel.com/) as mentors.

One theme of my doctoral research was the interplay between machine learning and strategic incentives. Another theme—the subject of my [dissertation](/assets/dissertation.pdf)—was using simple, mathematically well-defined tasks as model systems to study training dynamics and inductive biases in neural networks.

Before that, I undergraduated in math at Princeton and did computational complexity research.

<small> benedelman100@gmail.com | [Google Scholar](https://scholar.google.com/citations?user=mQSj2C0AAAAJ&hl=en) | [LinkedIn](https://www.linkedin.com/in/benjamin-edelman-24a610ab) | [X](https://x.com/EdelmanBen) </small>

## Research

**[Transcendence: Generative Models Can Outperform The Experts That Train Them](https://arxiv.org/abs/2406.11741)** <br>
Edwin Zhang, Vincent Zhu, Naomi Saphra, Anat Kleiman, **BE**, Milind Tambe, Sham M. Kakade, and Eran Malach
 <br>
*NeurIPS 2024* | [Blog post](https://kempnerinstitute.harvard.edu/research/deeper-learning/transcendence-generative-models-can-outperform-the-experts-that-train-them/)

**[The Evolution of Statistical Induction Heads: In-Context Learning Markov Chains](https://arxiv.org/abs/2402.11004)** <br>
**BE**, Ezra Edelman, Surbhi Goel, Eran Malach, and Nikolaos Tsilivis <br>
*NeurIPS 2024* | [Blog post](https://unprovenalgos.github.io/statistical-induction-heads)

**[Foundational Challenges in Assuring Alignment and Safety of Large Language Models](https://arxiv.org/abs/2404.09932)** <br>
Usman Anwar, Abulhair Saparov, Javier Rando, Daniel Paleka, Miles Turpin, Peter Hase, Ekdeep Singh Lubana, Erik Jenner, Stephen Casper, Oliver Sourbut, **BE**, Zhaowei Zhang, Mario Günther, Anton Korinek, Jose Hernandez-Orallo, and 27 others <br>
*TMLR, 2024* | [Webpage](https://llm-safety-challenges.github.io/)

**[Distinguishing the Knowable from the Unknowable with Language Models](https://arxiv.org/abs/2402.03563)** <br>
Gustaf Ahdritz, Tian Qin, Nikhil Vyas, Boaz Barak, and **BE** <br>
*ICML 2024* | [Blog post](https://kempnerinstitute.harvard.edu/research/deeper-learning/distinguishing-the-knowable-from-the-unknowable-with-language-models/)

**[Watermarks in the Sand: Impossibility of Strong Watermarking for Generative Models](https://arxiv.org/abs/2311.04378)** <br>
Hanlin Zhang, **BE**, Danilo Francati, Daniele Venturi, Giuseppe Ateniese, and Boaz Barak <br>
*ICML 2024, and Secure &amp; Trustworthy LLMs Workshop @ ICLR 2024* | [Blog post](https://kempnerinstitute.harvard.edu/research/deeper-learning/watermarking-in-the-sand/)

**[Feature Emergence via Margin Maximization: Case Studies in Algebraic Tasks](https://arxiv.org/abs/2311.07568)** <br>
Depen Morwani, **BE**, Costin-Andrei Oncescu, Rosie Zhao, and Sham Kakade <br>
*ICLR 2024 (spotlight)* | [Blog post](https://kempnerinstitute.harvard.edu/research/deeper-learning/where-do-features-come-from/)

{% for item in site.data.pubs %}
**[{{ item.title }}]({{ item.link }})** <br>
{{ item.coauthors }} <br>
*{{ item.venue }}*
{% endfor %}

## Theses
**[Combinatorial Tasks as Model Systems of Deep Learning](/assets/dissertation.pdf)** <br>
PhD Thesis

**[A Proof of Strassen’s Degree Bound for Homogeneous Arithmetic Circuits](/assets/senior_thesis.pdf)** <br>
Undergraduate Senior Thesis

## Teaching
<span>Spring 2021</span>{: class="date-brackets"} Teaching fellow for **CS 229br: Biology and Complexity** <br>
 Received Certificate of Distinction in Teaching from Harvard University

<span>Spring 2020</span>{: class="date-brackets"} Teaching fellow for **CS 228: Computational Learning Theory** <br>
Gave three lectures on "Mysteries of Generalization in Deep Learning"

## Tutorials
**[How to Achieve Both Transparency and Accuracy in Predictive Decision Making: An Introduction to Strategic Prediction](tutorial.html)** <br>
with Chara Podimata and Yonadav Shavit <br>
*FAccT 2021*

## Talks
<span>January &amp; March 2024</span>{: class="date-brackets"} Watermarks in the Sand: Impossibility of Strong Watermarking for Generative Models <br>
[NYC Crypto Day](https://nycryptoday.wordpress.com/2023/12/), [Boston Crypto Day](https://bostoncryptoday.wordpress.com/2024/02/)


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
