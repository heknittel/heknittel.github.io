---
title: "Generalized Reductions: Making any Hierarchical Clustering Fair and Balanced with Low Cost"
collection: publications
category: conferences
permalink: /publication/fhc2
excerpt: 'Near-polylogarithmic fair hierarchical clustering approximations for Dasgupta's cost function.'
date: 2023-07-23
venue: 'ICML'
paperurl: 'https://arxiv.org/abs/2205.14198'
bibtexurl: 'https://dblp.org/rec/conf/icml/KnittelSDH23.html?view=bibtex'
citation: 'Marina Knittel, Max Springer, John P. Dickerson, and MohammadTaghi Hajiaghayi. (2023). &quot;Generalized Reductions: Making any Hierarchical Clustering Fair and Balanced with Low Cost.&quot; <i>International Conference on Machine Learning</i>.'
---
Clustering is a fundamental building block of modern statistical analysis pipelines. Fair clustering has seen much attention from the machine learning community in recent years. We are some of the first to study fairness in the context of hierarchical clustering, after the results of Ahmadian et al. from NeurIPS in 2020. We evaluate our results using Dasgupta's cost function, perhaps one of the most prevalent theoretical metrics for hierarchical clustering evaluation. Our work vastly improves the previous $O(n^{5/6}poly\log(n))$ fair approximation for cost to a near polylogarithmic $O(n^\delta poly\log(n))$ fair approximation for any constant $\delta\in(0,1)$. This result establishes a cost-fairness tradeoff and extends to broader fairness constraints than the previous work. We also show how to alter existing hierarchical clusterings to guarantee fairness and cluster balance across any level in the hierarchy. 
