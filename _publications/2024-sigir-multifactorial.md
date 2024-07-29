---
title: "Going Beyond Popularity and Positivity Bias: Correcting for Multifactorial Bias in Recommender Systems"
authors: "Jin Huang, Harrie Oosterhuis, Masoud Mansoury, Herke van Hoof, and Maarten de Rijke"
collection: publications
permalink: /publication/2024-sigir-multifactorial
excerpt: "We consider multifactorial selection bias in RSs. Our focus is on selection bias affected by both item and rating value factors, which is a generalization and combination of popularity and positivity bias."
date: 2024-07-11
venue: 'Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval. (SIGIR ’24)'
paperurl: http://harrieo.github.io/files/2024-sigir-multifactorial.pdf
citation: "Huang, J., Oosterhuis, H., Mansoury, M., van Hoof, H., & de Rijke, M. (2024, July). Going Beyond Popularity and Positivity Bias: Correcting for Multifactorial Bias in Recommender Systems. In Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (pp. 416-426)."
youtube: 
codeurl: https://github.com/BetsyHJ/MultifactorialBias
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Two typical forms of bias in user interaction data with recommender systems (RSs) are popularity bias and positivity bias, which manifest themselves as the over-representation of interactions with popular items or items that users prefer, respectively. Debiasing methods aim to mitigate the effect of selection bias on the evaluation and optimization of RSs. However, existing debiasing methods only consider single-factor forms of bias, e.g., only the item (popularity) or only the rating value (positivity). This is in stark contrast with the real world where user selections are generally affected by multiple factors at once.

In this work, we consider multifactorial selection bias in RSs. Our focus is on selection bias affected by both item and rating value factors, which is a generalization and combination of popularity and positivity bias. While the concept of multifactorial bias is intuitive, it brings a severe practical challenge as it requires substantially more data for accurate bias estimation. As a solution, we propose smoothing and alternating gradient descent techniques to reduce variance and improve the robustness of its optimization. Our experimental results reveal that, with our proposed techniques, multifactorial bias corrections are more effective and robust than single-factor counterparts on real-world and synthetic datasets.
