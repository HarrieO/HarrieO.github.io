---
title: "Optimal Baseline Corrections for Off-Policy Contextual Bandits"
authors: "Shashank Gupta, Olivier Jeunen, Harrie Oosterhuis, and Maarten de Rijke"
collection: publications
permalink: /publication/2024-recsys-control-variates
excerpt: "The off-policy learning paradigm allows for recommender systems and general ranking applications to be framed as decision-making problems, where we aim to learn decision policies that optimize an unbiased offline estimate of an online reward metric. With unbiasedness comes potentially high variance, and prevalent methods exist to reduce estimation variance. These methods typically make use of control variates, either additive (i.e., baseline corrections or doubly robust methods) or multiplicative (i.e., self-normalisation)."
date: 2024-10-14
venue: 'Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM ’24)'
paperurl: http://harrieo.github.io/files/2024-recsys-control-variates.pdf
citation: "Gupta, S., Jeunen, O., Oosterhuis, H., & de Rijke, M. (2024, October). Optimal Baseline Corrections for Off-Policy Contextual Bandits. In Proceedings of the 18th ACM Conference on Recommender Systems (RecSys ’24)."
youtube: 
codeurl: https://github.com/shashankg7/recsys2024_optimal_baseline
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

The off-policy learning paradigm allows for recommender systems and general ranking applications to be framed as decision-making problems, where we aim to learn decision policies that optimize an unbiased offline estimate of an online reward metric. With unbiasedness comes potentially high variance, and prevalent methods exist to reduce estimation variance. These methods typically make use of control variates, either additive (i.e., baseline corrections or doubly robust methods) or multiplicative (i.e., self-normalisation).

Our work unifies these approaches by proposing a single framework built on their equivalence in learning scenarios. The foundation of our framework is the derivation of an equivalent baseline correction for all of the existing control variates. Consequently, our framework enables us to characterize the variance-optimal unbiased estimator and provide a closed-form solution for it. This optimal estimator brings significantly improved performance in both evaluation and learning, and minimizes data requirements. Empirical observations corroborate our theoretical findings.
