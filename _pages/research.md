---
layout: page
permalink: /research/
title: Research
description: I'm interested in multiple research areas and my papers can be broadly categorized as follows.
nav: true
nav_order: 2
---

#### Efficient NLP
With large language models becoming larger than ever, I believe efficiency of the architectures should be a constant question.
I am interested in building parameter-efficient and fast throughput architectures [<a href="https://arxiv.org/pdf/2211.16634">1</a>,<a href="https://arxiv.org/pdf/2302.12441.pdf">2</a>]
In an earlier work, we showed that even existing architectures like the Transformer can be made to converge significantly faster during pre-training by guiding their attention patterns <a href="https://arxiv.org/pdf/2010.02399.pdf">[3]</a>.

#### Zero and few-shot learning
Large language models should use efficient architectures, but should also be data-efficient during fine-tuning and inference.
In a series of two papers [<a href="https://arxiv.org/pdf/2202.13100">1</a>,<a href="https://arxiv.org/pdf/2301.11309">2</a>], we proposed a paradigm called semantic supervision which showed that representing classes not just symbolically but with a large number of semantic descriptions improves generalization to classes not seen during training.
Our method can help generalize to millions of classes in the extreme classification setting <a href="https://arxiv.org/pdf/2301.11309">[2]</a>.

#### Multilingual NLP
Democratization of NLP involves improve language technologies for all language, not just English.
I am interested in building better multilingual models, and that involves understanding the shortcomings of the current SOTA.
In a series of two papers [<a href="https://arxiv.org/pdf/2110.14782">1</a>,<a href="https://arxiv.org/pdf/2211.08547">2</a>] we showed that while multilingual pre-training objectives achieve impressive zero-shot cross-lingual transfer, they fail between very simple languages which differ only in their word order.
We hope this can motivate improvement in this line of work.

#### Reinforcement learning
I am particularly interested in how to use RL for NLP, and vice-versa.
We showed that using sentiment analysis to predict the sentiment of text observations can be useful for reward shaping <a href="https://arxiv.org/pdf/2010.02316">[1]</a>.
Previously, I have worked on inferring options from offline expert trajectories <a href="https://arxiv.org/pdf/1812.00225">[2]</a> and improving hindsigh learning <a href="https://arxiv.org/pdf/1809.06719">[3]</a>.