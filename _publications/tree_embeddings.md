---
title: "Massively Parallel Tree Embeddings for High Dimensional Spaces"
collection: publications
category: conferences
permalink: /publication/tree_embeddings
excerpt: 'Constant-round massively parallel algorithms for embedding high-dimensional data into trees.'
date: 2023-07-01
venue: 'SPAA'
paperurl: 'https://heknittel.github.io/files/Ahanchi_et_al_SPAA_2023.pdf'
bibtexurl: 'https://dblp.org/rec/conf/spaa/AhanchiAHKZ23.html?view=bibtex'
citation: 'AmirMohsen Ahanchi, Alexandr Andoni, MohammadTaghi Hajiaghayi, Marina Knittel, and Peilin Zhong. (2023). &quot;Massively Parallel Tree Embeddings for High Dimensional Spaces.&quot; <i>Symposium on Parallelism and Architectures</i>.'
---
Efficient computation on massive high-dimensional data greatly benefits from efficient embedding techniques into simpler metrics. Perhaps the most celebrated technique is the dimension reduction à-la Johnson and Lindenstrauss [46]. Another important method embeds the data into a tree metric space, first efficiently achieve by Bartal [15]. Both of these algorithmic tools are among the most general theorems with numerous applications.

In this paper, we study these two embedding methods in the Massively Parallel Computation (MPC) model. We develop a new hybrid partitioning algorithm which generalizes both random shifted grid and ball partitioning methods for generating tree embeddings. This leads to an $O(1)$-round randomized MPC algorithm for embedding high-dimensional data into a tree while approximating the distance between any two points within a factor of $O(\log^{1.5}(n))$ (and thus distortion $O(\log^{1.5}(n))$ in expectation as long as the aspect ratio is $O(poly(n))$. This Euclidean result beats the lower bound of $\Omega(\log n)$ MPC rounds for tree embeddings of general metric spaces and can extend to a number of problems, including densest ball, minimum spanning tree, and Earth-Mover distance. Along the way, we implement and use Ailon and Chazelle’s Fast Johnson Lindenstrauss Transform [2] with sublinear memory and $O(1)$ MPC rounds, which is of its own interest.
