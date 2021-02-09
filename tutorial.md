---
layout: no-sidebar
title: FAccT tutorial
---

# How to Achieve Both Transparency and Accuracy in Predictive Decision Making:<br>**An Introduction to Strategic Prediction**
{: class="post-title"}

### [FAccT 2021](https://facctconference.org/2021/index.html) Tutorial -- March 4th
{: style="text-align: center;"}
### [Ben Edelman](index.html), [Chara Podimata](https://www.charapodimata.com/), and [Yonadav Shavit](https://www.charapodimata.com/)
{: style="text-align: center;"}
---

## Motivation

> *When an algorithmic system holds sway over a person's life, the person has an incentive to respond to the algorithm strategically in order to obtain a more desirable decision.*

This is the mantra of the rapidly growing research area of *strategic prediction*. In short, as predictive decision-making algorithms become increasingly consequential, the standard assumption that data does not react to the model becomes increasingly false. Strategic adaptation to algorithms can be found all over society: e.g., a student memorizes the quirks of a standardized exam, a prospective homeowner lowers their credit card utilization, or a college tries to attract more applicants to decrease its acceptance rate.

Strategic prediction is a critical area of study because it holds the promise of making transparency more palatable to decision-makers. As those devoted to the project of just machine learning increasingly push for transparency and individual recourse as a means for ensuring humane predictive systems, they will continue to run into a fundamental resistance from decision-makers themselves. This is because decision-makers' foremost priority is the accuracy of their system. Allowing someone to understand their system perfectly threatens to increase "gaming", and thus undermine accuracy, so they calculate that it is better not to provide recourse at all. The field of strategic prediction has recently sprung up within computer science to answer a fundamental question:
> *How can we create machine learning systems that are accurate even when made transparent, and thus gamed by individuals?* [^1]



## Part 1: Introduction and the Robustness Perspective

We begin by introducing the motivation behind studying strategic classification in computer science. We illustrate the two normative objectives that are in conflict: *accuracy* and *transparency*. We highlight the tension by presenting a number of real-life settings where the strategic behavior of the agents can have adverse effects in the decision-making process (e.g., college admissions, car insurance, job search, credit scoring). We clarify the important difference between "gaming" and "improving" your outcome as an agent.[^2] For the remainder of the tutorial, we will be using college admissions as our running example. 

Next, we describe *at a high level* the useful notions of optimality that computer scientists use in the context of strategic classification: i.e., incentive-compatibility, Stackelberg equilibrium, and no-regret algorithms. We clarify that all these notions are introduced without any mathematical notation, as our goal is to familiarize participants from other disciplines with the literature. Lastly, we outline the key messages of papers from the robustness perspective ([Meir, Procaccia, Rosenschein '12](http://procaccia.info/wp-content/uploads/2012/07/spc.pdf), [Hardt, Megiddo, Papadimitriou, Wooters '16](https://arxiv.org/pdf/1506.06980.pdf), [Dong, Roth, Schutzman, Waggoner, Wu '18](https://arxiv.org/pdf/1710.07887.pdf), [Chen, Podimata, Procaccia, Shah '18](https://arxiv.org/pdf/1805.10693.pdf), [Chen, Liu, Podimata '20](https://arxiv.org/pdf/1911.04004.pdf), [Ahmadi, Beyhaghi, Blum, Naggita '20](https://arxiv.org/pdf/2008.01710.pdf)), the (potentially counterintuitive) importance of randomness, and conclude the session with some open questions.

## Part 2: Fairness and Recourse

Accepting the inevitable reality of strategic behavior leads to a host of fairness challenges facing the future of algorithms. In this session, we discuss the different ways that strategic behavior exacerbates bias. We focus on three sources of unfairness: different resources across groups leading some groups to be able to game more than others, different actions available to different groups leading to some being able to achieve greater recourse, and different initial features across groups leading to certain groups having an upper-bound on how good their prediction can be even if they exhaust every action available to them. We provide an overview of both the literature and related historical examples ([Hu, Immorlica, Vaughan '18](https://arxiv.org/pdf/1808.08646.pdf), [Milli, Miller, Dragan, Hardt '18](https://arxiv.org/pdf/1808.08460.pdf)).

In the next part, we highlight the close connection between recourse ([Ustun, Spangher, Liu '19](https://arxiv.org/pdf/1809.06514.pdf), [Chen, Wang, Liu '20](https://arxiv.org/pdf/2011.00355.pdf)) and strategic robustness. Recourse, or the ability of individuals to change their features 
to receive a better decision, is a property that benefits the individual but ultimately must be provided by the decision-maker. However, the decision-maker would suffer when providing recourse -- *unless* the classifier could be made strategically robust, in which case the decision-maker becomes willing to assist individuals in taking actions that lead to improved predictions. (Those improving individual predictions will, by the definition of a strategically-robust predictor, now correspond to individuals' improved true labels as well.) We discuss the differing focuses of whose utility is being considered (the institution or the individual) and how that leads to this literature's different framings (strategic classification and recourse). Our message will be that, in the end, neither is meaningful without the other.

## Part 3: Causal Perspective

In Session 3, we focus on the emerging literature on *causal* strategic learning. Prior work assumed that when an agent strategically alters their features, the outcome variable (i.e., the prediction's target) is unaffected: their manipulation is pure gaming. In contrast, a cluster of new papers considers the possibility that agents' strategic altering can cause genuine improvement in their true labels, which also benefits the decision-maker. For example, if an agent reduces their debt-to-income ratio to improve their credit score, they truly become less likely to default, and thus increase the profits of their lender. In this context, new objectives become natural. We give a taxonomy of these objectives ([Shavit, Edelman, Axelrod '20](https://arxiv.org/pdf/2002.10066.pdf)) and use it as a scaffolding for this part of the tutorial. In particular, we highlight papers that optimize for *model accuracy* ([Perdomo, Zrnic, Mendler-Dünner, Hardt '20](https://arxiv.org/pdf/2002.06673.pdf)), *improvement in agent outcomes* ([Kleinberg, Raghavan '19](https://arxiv.org/pdf/1807.05307.pdf), [Miller, Milli, Hardt '20](http://proceedings.mlr.press/v119/miller20b/miller20b-supp.pdf), [Haghtalab, Immorlica, Lucier, Wang '20](https://arxiv.org/pdf/2011.01956.pdf)), and *causal discovery* ([Bechavod, Ligett, Wu, Ziani '20](https://arxiv.org/pdf/2002.07024.pdf)). We touch on the connections with principal-agent problems from economics ([Salanie '05](https://www.google.com/books/edition/The_Economics_of_Contracts_second_editio/ySk3AgAAQBAJ)), and we conclude with open questions for scholars of different fields.



[^1]: And even opaque systems are rarely perfectly opaque, so strategic prediction is relevant in almost all predictive decision-making scenarios.

[^2]: For example, in college admissions, an agent who takes the SAT multiple times is "gaming" the decision making rule (through memorizing specific types of questions), while an agent who reads more books is "improving" their outcome.