---
title: "Learning against Non-credible Auctions"
collection: publications
category: conferences
posttype: academic
coauthor: Qian Wang, Xuanzhi Xia, Zongjun Yang, Xiaotie Deng, Yuqing Kong, Zhilin Zhang, Liang Wang, Chuan Yu, Jian Xu, Bo Zheng
permalink: /publication/2023-learning2
# excerpt: 'This paper is about fixing template issue #693.'
date: 2025-01-21
venue: 'The Web Conference (WWW)'
paperurl: 'https://arxiv.org/abs/2311.15203'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

The standard framework of online bidding algorithm design assumes that the seller commits himself to faithfully implementing the rules of the adopted auction. However, the seller may attempt to cheat in execution to increase his revenue if the auction belongs to the class of non-credible auctions. For example, in a second-price auction, the seller could create a fake bid between the highest bid and the second highest bid. This paper focuses on one such case of online bidding in repeated second-price auctions. At each time t, the winner with bid bt is charged not the highest competing bid dt but a manipulated price $$p_t=α_0d_t+(1−α_0)b_t$$, where the parameter $$α_0 \in [0,1]$$ in essence measures the seller's credibility. Unlike classic repeated-auction settings where the bidder has access to samples $$(d_s)_{s=1}^{t-1}$$, she can only receive mixed signals of $$(b_s)_{s=1}^{t-1}$$, $$(d_s)_{s=1}^{t-1}$$ and $$\alpha_0$$ in this problem. The task for the bidder is to learn not only the bid distributions of her competitors but also the seller's credibility. We establish regret lower bounds in various information models and provide corresponding online bidding algorithms that can achieve near-optimal performance. Specifically, we consider three cases of prior information based on whether the credibility $$\alpha_0$$ and the distribution of the highest competing bids are known. Our goal is to characterize the landscape of online bidding in non-credible auctions and understand the impact of the seller's credibility on online bidding algorithm design under different information structures. 

<!-- ---
title: "Paper Title Number 4"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about fixing template issue #693.'
date: 2024-02-17
venue: 'GitHub Journal of Bugs'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font. -->
