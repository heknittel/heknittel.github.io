---
title: "Matching Affinity Clustering: Improved Hierarchical Clustering at Scale with Guarantees"
collection: publications
category: conferences
permalink: /publication/mac
excerpt: 'Fast MPC hierarchical clustering algorithms with strong theoretical guarantees and empirical performance.'
date: 2020-05-01
venue: 'AAMAS'
paperurl: 'https://arxiv.org/abs/2101.04818'
bibtexurl: 'https://dblp.org/rec/conf/atal/HajiaghayiK20.html?view=bibtex'
citation: 'Marina Knittel and MohammadTaghi Hajiaghayi. (2023). &quot;Matching Affinity Clustering: Improved Hierarchical Clustering at Scale with Guarantees.&quot; <i>The International Conference on Autonomous Agents and Multiagent Systems</i>.'
---
Hierarchical clustering is a stronger extension of one of today's most influential unsupervised learning methods: clustering. The goal of this method is to create a hierarchy of clusters, thus constructing cluster evolutionary history and simultaneously finding clusterings at all resolutions. We propose four traits of interest for hierarchical clustering algorithms: (1) empirical performance, (2) theoretical guarantees, (3) cluster balance, and (4) scalability. While a number of algorithms are designed to achieve one to two of these traits at a time, there exist none that achieve all four.

Inspired by Bateni et al.'s scalable and empirically successful Affinity Clustering [NeurIPs 2017], we introduce Affinity Clustering's successor, Matching Affinity Clustering. Like its predecessor, Matching Affinity Clustering maintains strong empirical performance and uses Massively Parallel Communication as its distributed model. Designed to maintain provably balanced clusters, we show that our algorithm achieves good, constant factor approximations for Moseley and Wang's revenue and Cohen-Addad et al.'s value. We show Affinity Clustering cannot approximate either function. Along the way, we also introduce an efficient $k$-sized maximum matching algorithm in the MPC model. 
