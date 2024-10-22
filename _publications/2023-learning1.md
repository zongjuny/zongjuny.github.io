---
title: "Learning to Bid in Repeated First-Price Auctions with Budgets"
collection: publications
category: conferences
permalink: /publication/2023-learning1
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
coauthor: Qian Wang*, Zongjun Yang*, Xiaotie Deng, Yuqing Kong
date: 2023-01-01
venue: 'International Conference on Machine Learning (ICML)'
slidesurl: 'https://icml.cc/virtual/2023/poster/24350'
paperurl: 'https://arxiv.org/abs/2304.13477'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Budget management strategies in repeated auctions have received growing attention in online advertising markets. However, previous work on budget management in online bidding mainly focused on second-price auctions. The rapid shift from second-price auctions to first-price auctions for online ads in recent years has motivated the challenging question of how to bid in repeated first-price auctions while controlling budgets.
In this work, we study the problem of learning in repeated first-price auctions with budgets. We design a dual-based algorithm that can achieve a near-optimal $$\widetilde{O}(\sqrt{T})$$ regret with full information feedback where the maximum competing bid is always revealed after each auction. We further consider the setting with one-sided information feedback where only the winning bid is revealed after each auction. We show that our modified algorithm can still achieve an $$\widetilde{O}(\sqrt{T})$$ regret with mild assumptions on the bidder's value distribution. Finally, we complement the theoretical results with numerical experiments to confirm the effectiveness of our budget management policy. 