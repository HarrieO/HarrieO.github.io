---
title: "Proximal Ranking Policy Optimization for Practical Safety in Counterfactual Learning to Rank"
authors: "Shashank Gupta, Harrie Oosterhuis, Maarten de Rijke"
collection: publications
permalink: /publication/2024-consequences-proximal
excerpt: " We propose a novel approach, proximal ranking policy optimization (PRPO), that provides safety in deployment without assumptions about user behavior. PRPO removes incentives for learning ranking behavior that is too dissimilar to a safe ranking model."
date: 2024-10-14
venue: 'CONSEQUENCES Workshop at RecSys ’24. (CONSEQUENCES ’24)'
paperurl: http://harrieo.github.io/files/2024-consequences-proximal.pdf
citation: "Gupta S, Oosterhuis H, de Rijke M. (2024). Proximal Ranking Policy Optimization for Practical Safety in Counterfactual Learning to Rank. In CONSEQUENCES Workshop at RecSys ’24, October 14, 2024, Bari, Italy."
youtube: 
codeurl: https://github.com/shashankg7/cikm-safeultr
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Counterfactual learning to rank (CLTR) can be risky and, in various circumstances, can produce sub-optimal models that hurt performance when deployed. Safe CLTR was introduced to mitigate these risks when using inverse propensity scoring to correct for position bias. However, the existing safety measure for CLTR is not applicable to state-of-the-art CLTR methods, cannot handle trust bias, and relies on specific assumptions about user behavior. We propose a novel approach, proximal ranking policy optimization (PRPO), that provides safety in deployment without assumptions about user behavior. PRPO removes incentives for learning ranking behavior that is too dissimilar to a safe ranking model. Thereby, PRPO imposes a limit on how much learned models can degrade performance metrics, without relying on any specific user assumptions. Our experiments show that PRPO provides higher performance than the existing safe inverse propensity scoring approach. PRPO always maintains safety, even in maximally adversarial situations. By avoiding assumptions, PRPO is the first method with unconditional safety in deployment that translates to robust safety for real-world applications.
