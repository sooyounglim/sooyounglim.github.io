---
title: "Efficient Stack Distance Approximation Based on Workload Characteristics"
collection: publications
category: manuscripts
permalink: /publication/2022-IEEE-Access
excerpt: 'Sooyoung Lim and Dongchul Park'
date: 2022-06-06
venue: 'IEEE Access'
paperurl: '/files/papers/2022-IEEE-Access.pdf'
link: 'https://doi.org/10.1109/ACCESS.2022.3180327'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

A stack distance of a reference is the depth from which the reference must be extracted from a stack. It has been widely applied to a variety of applications utilizing temporal locality information. However, calculating an exact stack distance requires significant computational complexity that is impractical for online production systems. This paper proposes an efficient algorithm that approximates a stack distance based on workload characteristics. The proposed algorithm utilizes two simple reference metrics: inter-reference distance and a quasi-unique reference count. More importantly, its approximation algorithm requires surprisingly simple calculation. Consequently, it significantly reduces computational overhead while exhibiting exceptional accuracy and runs extremely fast. Moreover, it allows configurable parameters for performance optimization by making optimal use of workload characteristics. Our extensive experiments with diverse realistic workloads demonstrate our stack distance approximation algorithm outperforms the current state-of-the-art algorithm with higher accuracy ( 3.7× ), lower memory footprint ( 3.05× ) and fast execution (less than 0.05 seconds) on average. In addition, with configuration parameters, our refined algorithm can achieve a 28% average additional accuracy improvement.
