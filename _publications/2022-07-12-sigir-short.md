---
title: "Learning-to-Rank at the Speed of Sampling: Plackett-Luce Gradient Estimation With Minimal Computational Complexity"
authors: "Harrie Oosterhuis"
collection: publications
permalink: /publication/2022-sigir-short
excerpt: "In this paper, we introduce the novel PL-Rank-3 algorithm that performs unbiased gradient estimation with a computational complexity comparable to the best sorting algorithms."
date: 2022-07-12
venue: 'Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR ’22)'
paperurl: http://harrieo.github.io/files/2022-sigir-short.pdf
citation: "H. Oosterhuis. &quot;Learning-to-Rank at the Speed of Sampling: Plackett-Luce Gradient Estimation With Minimal Computational Complexity.&quot; In <i>Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval</i>. ACM, 2022."
youtube: K-5nruyS6Fg
codeurl: https://github.com/HarrieO/2022-SIGIR-plackett-luce
othervideo:
tutorialwebsite: 
slides: /files/slides/2022-sigir-short.pdf
poster: /files/posters/2022-sigir-poster.pdf
---

Plackett-Luce gradient estimation enables the optimization of stochastic ranking models within feasible time constraints through sampling techniques. Unfortunately, the computational complexity of existing methods does not scale well with the length of the rankings, i.e. the ranking cutoff, nor with the item collection size.

In this paper, we introduce the novel PL-Rank-3 algorithm that performs unbiased gradient estimation with a computational complexity comparable to the best sorting algorithms. As a result, our novel learning-to-rank method is applicable in any scenario where standard sorting is feasible in reasonable time. Our experimental results indicate large gains in the time required for optimization, without any loss in performance. For the field, our contribution could potentially allow state-of-the-art learning-to-rank methods to be applied to much larger scales than previously feasible.