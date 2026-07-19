---
title: "Learning against Non-credible Auctions"
collection: publications
category: conferences
posttype: academic
coauthor: Joint work with Qian Wang, Xuanzhi Xia, Xiaotie Deng, Yuqing Kong, Zhilin Zhang, Liang Wang, Chuan Yu, Jian Xu, and Bo Zheng
permalink: /publication/2023-learning2
date: 2025-01-21
venue: 'The ACM Web Conference'
venue_abbreviation: "WWW'25"
paperurl: 'https://arxiv.org/abs/2311.15203'
---

The standard framework of online bidding algorithm design assumes that the seller commits himself to faithfully implementing the rules of the adopted auction. However, the seller may attempt to cheat in execution to increase his revenue if the auction belongs to the class of non-credible auctions. For example, in a second-price auction, the seller could create a fake bid between the highest bid and the second highest bid. This paper focuses on one such case of online bidding in repeated second-price auctions. At each time t, the winner with bid bt is charged not the highest competing bid dt but a manipulated price $$p_t=α_0d_t+(1−α_0)b_t$$, where the parameter $$α_0 \in [0,1]$$ in essence measures the seller's credibility. Unlike classic repeated-auction settings where the bidder has access to samples $$(d_s)_{s=1}^{t-1}$$, she can only receive mixed signals of $$(b_s)_{s=1}^{t-1}$$, $$(d_s)_{s=1}^{t-1}$$ and $$\alpha_0$$ in this problem. The task for the bidder is to learn not only the bid distributions of her competitors but also the seller's credibility. We establish regret lower bounds in various information models and provide corresponding online bidding algorithms that can achieve near-optimal performance. Specifically, we consider three cases of prior information based on whether the credibility $$\alpha_0$$ and the distribution of the highest competing bids are known. Our goal is to characterize the landscape of online bidding in non-credible auctions and understand the impact of the seller's credibility on online bidding algorithm design under different information structures. 
