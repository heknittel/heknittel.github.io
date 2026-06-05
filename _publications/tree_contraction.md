---
title: "Adaptive Massively Parallel Constant-round Tree Contraction"
collection: publications
category: conferences
permalink: /publication/tree_contraction
excerpt: '<sup>abc</sup> [MohammadTaghi Hajiaghayi](https://www.cs.umd.edu/~hajiagha/), Marina Knittel, [Hamed Saleh](https://scholar.google.com/citations?user=8t3aDXgAAAAJ&hl=en), and [Hsin-Hao Su](https://sites.google.com/site/distributedhsinhao/).'
date: 2022-01-01
venue: 'ITCS'
paperurl: 'https://arxiv.org/abs/2111.01904'
bibtexurl: 'dblp.org/rec/conf/innovations/HajiaghayiKSS22.html?view=bibtex'
---
Miller and Reif's FOCS'85 classic and fundamental tree contraction algorithm is a broadly applicable technique for the parallel solution of a large number of tree problems. Additionally it is also used as an algorithmic design technique for a large number of parallel graph algorithms. In all previously explored models of computation, however, tree contractions have only been achieved in $\Omega(n)$ rounds of parallel run time. In this work, we not only introduce a generalized tree contraction method but also show it can be computed highly efficiently in $O(1/\epsilon^3)$ rounds in the Adaptive Massively Parallel Computing (AMPC) setting, where each machine has $O(n^\epsilon)$ local memory for some $0 < \epsilon < 1$. AMPC is a practical extension of Massively Parallel Computing (MPC) which utilizes distributed hash tables. In general, MPC is an abstract model for MapReduce, Hadoop, Spark, and Flume which are currently widely used across industry and has been studied extensively in the theory community in recent years. Last but not least, we show that our results extend to multiple problems on trees, including but not limited to maximum and maximal matching, maximum and maximal independent set, tree isomorphism testing, and more. 

<span style="color:grey"><small>MohammadTaghi Hajiaghayi, Marina Knittel, Hamed Saleh, and Hsin-Hao Su. **Adaptive Massively Parallel Constant-round Tree Contraction.** *Innovations in Theoretical Computer Science,* 2022.</small></span>
