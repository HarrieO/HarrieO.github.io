---
title: "Practical and Robust Safety Guarantees for Advanced Counterfactual Learning to Rank"
authors: "Shashank Gupta, Harrie Oosterhuis, and Maarten de Rijke"
collection: publications
permalink: /publication/2024-cltr-safety
excerpt: "Our contributions are two-fold. First, we generalize the existing safe CLTR approach to make it applicable to state-of-the-art doubly robust CLTR and trust bias. Second, we propose a novel approach, proximal ranking policy optimization (PRPO), that provides safety in deployment without assumptions about user behavior. PRPO removes incentives for learning ranking behavior that is too dissimilar to a safe ranking model."
date: 2024-10-21
venue: 'Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM ’24)'
paperurl: http://harrieo.github.io/files/2024-crm-ppo.pdf
citation: "Gupta, S., Oosterhuis, H., & de Rijke, M. (2024, October). Practical and Robust Safety Guarantees for Advanced Counterfactual Learning to Rank. In Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM ’24)."
youtube: 
codeurl: https://github.com/shashankg7/cikm-safeultr
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Counterfactual learning to rank (CLTR) can be risky and, in various circumstances, can produce sub-optimal models that hurt perfor- mance when deployed. Safe CLTR was introduced to mitigate these risks when using inverse propensity scoring to correct for position bias. However, the existing safety measure for CLTR is not applicable to state-of-the-art CLTR methods, cannot handle trust bias, and relies on specific assumptions about user behavior.

Our contributions are two-fold. First, we generalize the existing safe CLTR approach to make it applicable to state-of-the-art doubly robust CLTR and trust bias. Second, we propose a novel approach, proximal ranking policy optimization (PRPO), that provides safety in deployment without assumptions about user behavior. PRPO removes incentives for learning ranking behavior that is too dissimilar to a safe ranking model. Thereby, PRPO imposes a limit on how much learned models can degrade performance metrics, without relying on any specific user assumptions. Our experiments show that both our novel safe doubly robust method and PRPO pro- vide higher performance than the existing safe inverse propensity scoring approach. However, in unexpected circumstances, the safe doubly robust approach can become unsafe and bring detrimental performance. In contrast, PRPO always maintains safety, even in maximally adversarial situations. By avoiding assumptions, PRPO is the first method with unconditional safety in deployment that translates to robust safety for real-world applications.