---
title: "DREAM: An Algorithm for Mitigating the Overhead of Robust Rescheduling"
collection: publications
category: conferences
permalink: /publication/dream
excerpt: 'Jordan R. Abrahams, David A. Chu, Grace Diehl, Marina Knittel, Judy Lin, William Lloyd, [James C. Boerkoel Jr.](https://www.cs.hmc.edu/~boerkoel/), and [Jeremy Frank](https://ti.arc.nasa.gov/profile/frank/).'
date: 2019-07-01
venue: 'ICAPS'
paperurl: 'https://heknittel.github.io/files/Abrahams_et_al_ICAPS_2019.pdf'
bibtexurl: 'https://dblp.org/rec/conf/aips/AbrahamsCDKLLBJ19.html?view=bibtex'
---
Generating and executing temporal plans is difficult in uncertain environments. The current state-of-the-art algorithm for probabilistic temporal networks maintains a high success rate by rescheduling frequently as uncertain events are resolved, but this approach involves substantial resource overhead due to computing and communicating new schedules between agents. Aggressive rescheduling could thus reduce overall mission duration or success in situations where agents have limited energy or computing power, and may not be feasible when communication is limited. In this paper, we propose new approaches for heuristically deciding when rescheduling is most efficacious. We propose two compatible approaches, Allowable Risk and Sufficient Change, that can be employed in combination to compromise between the computation rate, the communication rate, and success rate for new schedules. We show empirically that both approaches allow us to gracefully trade success rate for lower computation and/or communication as compared to the state-of-the-art dynamic scheduling algorithm.

<span style="color:grey"><small>Jordan R. Abrahams, David A. Chu, Grace Diehl, Marina Knittel, Judy Lin, William Lloyd, James C. Boerkoel Jr., and Jeremy Frank. **DREAM: An Algorithm for Mitigating the Overhead of Robust Rescheduling.** *The 29th International Conference on Automated Planning and Scheduling,* 2019.</small></span>
