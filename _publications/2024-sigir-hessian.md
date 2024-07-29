---
title: "Estimating the Hessian Matrix of Ranking Objectives for Stochastic Learning to Rank with Gradient Boosted Trees"
authors: "Jingwei Kang, Maarten de Rijke, and Harrie Oosterhuis"
collection: publications
permalink: /publication/2024-sigir-hessian
excerpt: "We introducing the first stochastic LTR method for GBDTs. Our main contribution is a novel estimator for the second-order derivatives, i.e., the Hessian matrix, which is a requirement for effective GBDTs. To efficiently compute both the first and second-order derivatives simultaneously, we incorporate our estimator into the existing PL-Rank framework."
date: 2024-07-11
venue: 'Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval. (SIGIR ’24)'
paperurl: http://harrieo.github.io/files/2024-sigir-hessian.pdf
citation: "Kang, J., de Rijke, M., & Oosterhuis, H. (2024, July). Estimating the Hessian Matrix of Ranking Objectives for Stochastic Learning to Rank with Gradient Boosted Trees. In Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (pp. 2390-2394)."
youtube: 
codeurl: https://github.com/BetsyHJ/MultifactorialBias
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Stochastic learning to rank (LTR) is a recent branch in the LTR field that concerns the optimization of probabilistic ranking models. Their probabilistic behavior enables certain ranking qualities that are impossible with deterministic models. For example, they can increase the diversity of displayed documents, increase fairness of exposure over documents, and better balance exploitation and exploration through randomization. A core difficulty in LTR is gradient estimation, for this reason, existing stochastic LTR methods have been limited to differentiable ranking models (e.g., neural networks). This is in stark contrast with the general field of LTR where Gradient Boosted Decision Trees (GBDTs) have long been considered the state-of-the-art. In this work, we address this gap by introducing the first stochastic LTR method for GBDTs. Our main contribution is a novel estimator for the second-order derivatives, i.e., the Hessian matrix, which is a requirement for effective GBDTs. To efficiently compute both the first and second-order derivatives simultaneously, we incorporate our estimator into the existing PL-Rank framework, which was originally designed for first-order derivatives only. Our experimental results indicate that stochastic LTR without the Hessian has extremely poor performance, whilst the performance is competitive with the current state-of-the-art with our estimated Hessian. Thus, through the contribution of our novel Hessian estimation method, we have successfully introduced GBDTs to stochastic LTR.
