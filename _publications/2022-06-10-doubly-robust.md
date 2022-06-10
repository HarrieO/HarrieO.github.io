---
title: "Doubly-Robust Estimation for Correcting Position-Bias in Click Feedback for Unbiased Learning to Rank"
authors: "Harrie Oosterhuis"
collection: publications
permalink: /publication/2022-doubly-robust
excerpt: "In this paper, we introduce a novel DR estimator that is the first DR approach specifically designed for position-bias. The difficulty with position bias is that the treatment – user examination – is not directly observable in click data. As a solution, our estimator uses the expected treatment per rank, instead of the actual treatment that existing DR estimators use."
date: 2022-06-10
venue: 'Arxiv Preprint (Currently Under Review Elsewhere)'
paperurl: http://harrieo.github.io/files/2022-doubly-robust.pdf
citation: "H. Oosterhuis. &quot;Learning-to-Rank at the Speed of Sampling: Plackett-Luce Gradient Estimation With Minimal Computational Complexity.&quot; arXiv preprint arXiv:2203.17118 (2022)."
youtube: 
codeurl: https://github.com/HarrieO/2022-doubly-robust-LTR
othervideo:
tutorialwebsite: 
slides: 
---

Clicks on rankings suffer from position bias: generally items on lower ranks are less likely to be examined - and thus clicked - by users, in spite of their actual preferences between items. The prevalent approach to unbiased click-based learning-to-rank (LTR) is based on counterfactual inverse-propensity-scoring (IPS) estimation. In contrast with general reinforcement learning, counterfactual doubly-robust (DR) estimation has not been applied to click-based LTR in previous literature.

In this paper, we introduce a novel DR estimator that is the first DR approach specifically designed for position-bias. The difficulty with position bias is that the treatment - user examination - is not directly observable in click data. As a solution, our estimator uses the expected treatment per rank, instead of the actual treatment that existing DR estimators use. Our novel DR estimator has more robust unbiasedness conditions than the existing IPS approach, and in addition, provides enormous decreases in variance: our experimental results indicate it requires several orders of magnitude fewer datapoints to converge at optimal performance. For the unbiased LTR field, our DR estimator contributes both increases in state-of-the-art performance and the most robust theoretical guarantees of all known LTR estimators.