---
title: "Reaching the End of Unbiasedness: Uncovering Implicit Limitations of Click-Based Learning to Rank"
authors: "Harrie Oosterhuis"
collection: publications
permalink: /publication/2022-ictir-future-unbiased
excerpt: "This work aims to uncover the implicit limitations of the high-level prevalent approach in the counterfactual LTR field. Thus, in contrast with limitations that follow from explicit assumptions, our aim is to recognize limitations that the field is currently unaware of."
date: 2022-07-12
venue: 'Proceedings of the 2022 ACM SIGIR International Conference on the Theory of Information Retrieval (ICTIR `22)'
paperurl: http://harrieo.github.io/files/2022-ictir-future-unbiased.pdf
citation: "H. Oosterhuis. &quot;Reaching the End of Unbiasedness: Uncovering Implicit Limitations of Click-Based Learning to Rank.&quot; In <i>Proceedings of the 2022 ACM SIGIR International Conference on the Theory of Information Retrieval</i>. ACM, 2022."
youtube: 
award: 
codeurl: 
slides: 
---

Click-based learning to rank (LTR) tackles the mismatch between click frequencies on items and their actual relevance. The approach of previous work has been to assume a model of click behavior and to subsequently introduce a method for unbiasedly estimating preferences under that assumed model. The success of this approach is evident in that unbiased methods have been found for an increasing number of behavior models and types of bias.

This work aims to uncover the implicit limitations of the high-level prevalent approach in the counterfactual LTR field. Thus, in contrast with limitations that follow from explicit assumptions, our aim is to recognize limitations that the field is currently unaware of. We do this by inverting the existing approach: we start by capturing existing methods in generic terms, and subsequently, from these generic descriptions we derive the click behavior for which these methods can be unbiased. Our inverted approach reveals that there are indeed implicit limitations to the counterfactual LTR approach: we find counterfactual estimation can only produce unbiased methods for click behavior based on affine transformations. In addition, we also recognize previously undiscussed limitations of click-modelling and pairwise approaches to click-based LTR. Our findings reveal that it is impossible for existing approaches to provide unbiasedness guarantees for all plausible click behavior models.