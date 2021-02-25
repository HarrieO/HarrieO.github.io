---
title: "Balancing Speed and Quality in Online Learning to Rank for Information Retrieval"
authors: "Harrie Oosterhuis and Maarten de Rijke"
collection: publications
permalink: /publication/2017-balancing
excerpt: "Effective optimization is essential for interactive systems to provide a satisfactory user experience. However, it is often challenging to find an objective to optimize for. Generally, such objectives are manually crafted and rarely capture complex user needs accurately. Conversely, we propose an approach that infers the objective directly from observed user interactions."
date: 2017-11-06
venue: 'Proceedings of the 2017 ACM on Conference on Information and Knowledge Management (CIKM ’17)'
paperurl: http://harrieo.github.io/files/2017-balancing.pdf
citation: "H. Oosterhuis, M. de Rijke. &quot;Balancing Speed and Quality in Online Learning to Rank for Information Retrieval.&quot; In <i>Proceedings of the 2017 ACM on Conference on Information and Knowledge Management</i>. ACM, 2017."
youtube: 
codeurl: https://github.com/HarrieO/BalancingSpeedQualityOLTR
othervideo:
tutorialwebsite:
slides:
---

In Online Learning to Rank (OLTR) the aim is to find an optimal ranking model by interacting with users. When learning from user behavior, systems must interact with users while simultaneously learning from those interactions. Unlike other Learning to Rank (LTR) settings, existing research in this field has been limited to linear models. This is due to the speed-quality tradeoff that arises when selecting models: complex models are more expressive and can find the best rankings but need more user interactions to do so, a requirement that risks frustrating users during training. Conversely, simpler models can be optimized on fewer interactions and thus provide a better user experience, but they will converge towards suboptimal rankings. This tradeoff creates a deadlock, since novel models will not be able to improve either the user experience or the final convergence point, without sacrificing the other.

Our contribution is twofold. First, we introduce a fast OLTR model called Sim-MGD that addresses the speed aspect of the speed-quality tradeoff. Sim-MGD ranks documents based on similarities with reference documents. It converges rapidly and, hence, gives a better user experience but it does not converge towards the optimal rankings. Second, we contribute Cascading Multileave Gradient De- scent (C-MGD) for OLTR that directly addresses the speed-quality tradeoff by using a cascade that enables combinations of the best of two worlds: fast learning and high quality final convergence. C-MGD can provide the better user experience of Sim-MGD while maintaining the same convergence as the state-of-the-art MGD model. This opens the door for future work to design new models for OLTR without having to deal with the speed-quality tradeoff.