---
title: "Sensitive and Scalable Online Evaluation with Theoretical Guarantees"
authors: "Harrie Oosterhuis and Maarten de Rijke"
collection: publications
permalink: /publication/2017-multileave
excerpt: "Our contribution is two-fold. First, we propose a theoretical framework for systematically comparing multileaved comparison methods using the notions of considerateness, which concerns maintaining the user experience, and fidelity, which concerns reliable correct outcomes. Second, we introduce a novel multileaved comparison method, Pairwise Preference Multileaving (PPM)."
date: 2017-11-06
venue: 'Proceedings of the 2017 ACM on Conference on Information and Knowledge Management (CIKM ’17)'
paperurl: http://harrieo.github.io/files/2017-multileave.pdf
citation: "H. Oosterhuis, M. de Rijke. &quot;Sensitive and Scalable Online Evaluation with Theoretical Guarantees.&quot; In <i>Proceedings of the 2017 ACM on Conference on Information and Knowledge Management.</i>. ACM, 2017."
youtube: 
codeurl: https://github.com/HarrieO/PairwisePreferenceMultileave
othervideo:
tutorialwebsite:
slides:
---

Multileaved comparison methods generalize interleaved comparison methods to provide a scalable approach for comparing ranking systems based on regular user interactions. Such methods enable the increasingly rapid research and development of search engines. However, existing multileaved comparison methods that provide reliable outcomes do so by degrading the user experience during evaluation. Conversely, current multileaved comparison methods that maintain the user experience cannot guarantee correctness. Our contribution is two-fold. First, we propose a theoretical framework for systematically comparing multileaved comparison methods using the notions of considerateness, which concerns maintaining the user experience, and fidelity, which concerns reliable correct outcomes. Second, we introduce a novel multileaved comparison method, Pairwise Preference Multileaving (PPM), that performs comparisons based on document-pair preferences, and prove that it is considerate and has fidelity. We show empirically that, compared to previous multileaved comparison methods, PPM is more sensitive to user preferences and scalable with the number of rankers being compared.