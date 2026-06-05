---
title: "Streaming and Massively Parallel Algorithms for Edge Coloring"
collection: publications
category: conferences
permalink: /publication/edge_coloring
excerpt: '<sup>abc</sup>[Soheil Behnezhad](http://behnezhad.com/), [Mahsa Derakhshan](http://cs.umd.edu/~mahsa/), [MohammadTaghi Hajiaghayi](https://www.cs.umd.edu/~hajiagha/), Marina Knittel, and [Hamed Saleh](https://scholar.google.com/citations?user=8t3aDXgAAAAJ&hl=en).'
date: 2019-09-01
venue: 'ESA'
paperurl: 'https://heknittel.github.io/files/behnezhad_et_al_ESA_2019.pdf'
bibtexurl: 'https://dblp.org/rec/conf/esa/BehnezhadDHKS19.html?view=bibtex'
---
A valid edge-coloring of a graph is an assignment of “colors” to its edges such that no two incident edges receive the same color. The goal is to find a proper coloring that uses few colors. (Note that the maximum degree, $\Delta$, is a trivial lower bound.) In this paper, we revisit this fundamental problem in two models of computation specific to massive graphs, the Massively Parallel Computations (MPC) model and the Graph Streaming model:

Massively Parallel Computation. We give a randomized MPC algorithm that with high probability returns a $\Delta _ \tilde{O}(\Delta^{3/4})$ edge coloring in $O(1)$ rounds using $O(n)$ space per machine and $O(m)$ total space. The space per machine can also be further improved to $n^{1-\Omega(1)}$ if $\Delta = n^{\Omega(1)}$. Our algorithm improves upon a previous result of Harvey et al. [SPAA 2018].

Graph Streaming. Since the output of edge-coloring is as large as its input, we consider a standard variant of the streaming model where the output is also reported in a streaming fashion. The main challenge is that the algorithm cannot “remember” all the reported edge colors, yet has to output a proper edge coloring using few colors.

We give a one-pass $\tilde{O}(n)$-space streaming algorithm that always returns a valid coloring and uses $5.44\Delta$ colors with high probability if the edges arrive in a random order. For adversarial order streams, we give another one-pass $\tilde{O}(n)$-space algorithm that requires $O(\Delta^2)$ colors.

<span style="color:grey"><small>Soheil Behnezhad, Mahsa Derakhshan, MohammadTaghi Hajiaghayi, Marina Knittel, and Hamed Saleh. **Streaming and Massively Parallel Algorithms for Edge Coloring.** *The 27th Annual European Symposium on Algorithms,* 2019.</small></span>
