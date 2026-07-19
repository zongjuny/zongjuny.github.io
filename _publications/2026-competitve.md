---
title: "Competitive Equilibrium in Labor Economies through the Lens of Goods and Chores Fisher Markets"
collection: publications
category: conferences
posttype: academic
coauthor: Joint work with Bhaskar Ray Chaudhury, Christian Kroer, Ruta Mehta, and Tianlong Nan 
permalink: /publication/2026-competitive
date: 2026-05-18
venue: 'ACM Conference on Economics and Computation'
venue_abbreviation: "EC'26"
paperurl: 'https://arxiv.org/abs/2606.15060'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---
The Fisher market with goods has been studied extensively in the algorithmic game theory literature, yielding strong algorithmic results for computing competitive equilibria. In contrast, more recent work on Fisher markets with bads or chores has shown that the equilibrium set can be nonconvex, making equilibrium computation considerably more challenging.

In this paper, we study a two-sided labor market that couples the classical Fisher market with goods and the Fisher market with bads into a single unified framework. In our model, users demand tasks in order to derive utility, while workers supply labor by performing these tasks in exchange for earnings. Each task thus plays a dual role: it is a good for the consumption (user) side of the market and a chore for the production (worker) side. Given prices for tasks, users choose utility-maximizing bundles subject to budgets, while workers choose disutility-minimizing task bundles subject to earning requirements; the resulting choices induce demand and supply endogenously for each task, and a competitive equilibrium corresponds to prices at which these coincide. We start by showing that such markets are guaranteed to have equilibria in a very general setting with concave utilities on the goods side and convex disutilities on the chores side of the market. Moreover, we show that the optimality guarantees of the first and second welfare theorems hold for our labor market model.

We next study the computation of equilibria under linear preferences. We show that, similar to the chores setting, equilibria correspond to KKT points of an Eisenberg-Gale-like non-convex program. Despite the non-convex characterization arising from the chores side of the market, we go on to show a set of surprisingly positive results. First, we show that there exists a polynomial-time combinatorial algorithm for computing competitive equilibria in our setting, which relies on a natural Walrasian scheme for updating prices. In the "CEEI-like" case where the budgets and earning requirements on each side of the market are all one, this yields a strongly polynomial-time algorithm.

Similar to recent results in the chores setting, we next show that our market admits a natural dual program, in spite of the non-convexity of both the primal and dual programs. Unlike the chores setting, we then show that the non-convex labor-market program admits a change of variables that transform it into a linear program (albeit with irrational coefficients). Finally, leveraging this linear program, we give yet another polynomial-time algorithm for computing a competitive equilibrium while deriving an approach for addressing the irrational coefficients on the linear program in an efficient manner. We note that, even for goods-only linear Fisher markets, obtaining such an LP formulation remains open.
<!-- ---
