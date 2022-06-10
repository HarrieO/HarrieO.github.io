---
title: "Computationally Efficient Optimization of Plackett-Luce Ranking Models for Relevance and Fairness (Extended Abstract)"
authors: "Harrie Oosterhuis"
collection: publications
permalink: /publication/2022-ijcai-abstract
excerpt: "In this paper, we introduce a novel algorithm: PL-Rank, that estimates the gradient of a PL ranking model w.r.t. both relevance and fairness metrics. Unlike existing approaches that are based on policy gradients, PL-Rank makes use of the specific structure of PL models and ranking metrics."
date: 2022-07-24
venue: 'Proceedings of the Thirty-First International Joint Conference on Artificial Intelligence (IJCAI ’22)'
paperurl: http://harrieo.github.io/files/2022-ijcai-abstract.pdf
citation: "H. Oosterhuis. &quot;Computationally Efficient Optimization of Plackett-Luce Ranking Models for Relevance and Fairness (Extended Abstract).&quot; In <i>Proceedings of the Thirty-First International Joint Conference on Artificial Intelligence</i>. International Joint Conferences on Artificial Intelligence, 2022."
youtube: heHOcTkgHB8
award: 
codeurl: https://github.com/HarrieO/2021-SIGIR-plackett-luce
slides: /files/slides/2021-sigir.pdf
---

Recent work has proposed stochastic Plackett-Luce (PL) ranking models as a robust choice for optimizing relevance and fairness metrics. Unlike their deterministic counterparts that require heuristic optimization algorithms, PL models are fully differentiable. Theoretically, they can be used to optimize ranking metrics via stochastic gradient descent. However, in practice, the computation of the gradient is infeasible because it requires one to iterate over all possible permutations of items. Consequently, actual applications rely on approximating the gradient via sampling techniques.

In this paper, we introduce a novel algorithm: PL-Rank, that estimates the gradient of a PL ranking model w.r.t. both relevance and fairness metrics. Unlike existing approaches that are based on policy gradients, PL-Rank makes use of the specific structure of PL models and ranking metrics. Our experimental analysis shows that PL-Rank has a greater sample-efficiency and is computationally less costly than existing policy gradients, resulting in faster convergence at higher performance. PL-Rank further enables the industry to apply PL models for more relevant and fairer real-world ranking systems.

The paper on which this an abstract is based can be found [here](2021-plrank).