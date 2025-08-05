---
title: "A Simpler Alternative to Variational Regularized Counterfactual Risk Minimization"
authors: "Hua Chang Bakker, Shashank Gupta, Harrie Oosterhuis"
collection: publications
permalink: /publication/2024-consequences-simpler
excerpt: "In this work, we revisit the original experimental setting of VRCRM and propose to minimize the f-divergence directly, instead of optimizing for the lower bound using a f-GAN approach. Surprisingly, we were unable to reproduce the results reported in the original setting. In response, we propose a novel simpler alternative to f-divergence optimization by minimizing a direct approximation of f-divergence directly, instead of a f-GAN based lower bound."
date: 2024-10-14
venue: 'CONSEQUENCES Workshop at RecSys ’24. (CONSEQUENCES ’24)'
paperurl: http://harrieo.github.io/files/2024-consequences-simpler.pdf
citation: "Bakker, H.C., Gupta, S. and Oosterhuis, H. (2024). Simpler Alternative to Variational Regularized Counterfactual Risk Minimization. In CONSEQUENCES Workshop at RecSys ’24, October 14, 2024, Bari, Italy."
youtube: 
codeurl: https://github.com/hang-wu/VRCRM
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Variance regularized counterfactual risk minimization (VRCRM) has been proposed as an alternative off-policy learning (OPL) method. VRCRM method uses a lower-bound on the f-divergence between the logging policy and the target policy as regularization during learning and was shown to improve performance over existing OPL alternatives on multi-label classification tasks. In this work, we revisit the original experimental setting of VRCRM and propose to minimize the f-divergence directly, instead of optimizing for the lower bound using a f-GAN approach. Surprisingly, we were unable to reproduce the results reported in the original setting. In response, we propose a novel simpler alternative to f-divergence optimization by minimizing a direct approximation of f-divergence directly, instead of a f-GAN based lower bound. Experiments showed that minimizing the divergence using f-GANs did not work as expected, whereas our proposed novel simpler alternative works better empirically.
