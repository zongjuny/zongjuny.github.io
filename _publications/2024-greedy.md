---
title: "Greedy-Based Online Fair Allocation with Adversarial Input: Enabling Best-of-Many-Worlds Guarantees"
collection: publications
category: conferences
posttype: academic
permalink: /publication/2024-greedy
excerpt: '*Superceded by "Online Fair Allocation with Best-of-Many-Worlds Guarantees"*'
coauthor: Joint work with Luofeng Liao and Christian Kroer
date: 2024-02-01
venue: 'AAAI Conference on Artificial Intelligence'
venue_abbreviation: "AAAI'24"
paperurl: 'https://arxiv.org/abs/2308.09277'
---

We study an online allocation problem with sequentially arriving items and adversarially chosen agent values, with the goal of balancing fairness and efficiency. Our goal is to study the performance of algorithms that achieve strong guarantees under other input models such as stochastic inputs, in order to achieve robust guarantees against a variety of inputs. To that end, we study the PACE (Pacing According to Current Estimated utility) algorithm, an existing algorithm designed for stochastic input. We show that in the equal-budgets case, PACE is equivalent to the integral greedy algorithm. We go on to show that with natural restrictions on the adversarial input model, both integral greedy allocation and PACE have asymptotically bounded multiplicative envy as well as competitive ratio for Nash welfare, with the multiplicative factors either constant or with optimal order dependence on the number of agents. This completes a "best-of-many-worlds" guarantee for PACE, since past work showed that PACE achieves guarantees for stationary and stochastic-but-non-stationary input models. 
