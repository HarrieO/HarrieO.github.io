---
title: "The Bandwagon Effect: Not Just Another Bias"
authors: "Norman Knyazev and Harrie Oosterhuis"
collection: publications
permalink: /publication/2022-ictir-bandwagon
excerpt: "We argue that the bandwagon effect should not be seen as a problem of statistical bias. In fact, we prove that this effect leaves both individual interactions and their sample mean unbiased. Nevertheless, we show that it can make estimators inconsistent, introducing a distinct set of problems for convergence in relevance estimation."
date: 2022-07-12
venue: 'Proceedings of the 2022 ACM SIGIR International Conference on the Theory of Information Retrieval (ICTIR ’22)'
paperurl: http://harrieo.github.io/files/2022-ictir-future-unbiased.pdf
citation: "N. Knyazev and H. Oosterhuis. &quot;The Bandwagon Effect: Not Just Another Bias.&quot; In <i>Proceedings of the 2022 ACM SIGIR International Conference on the Theory of Information Retrieval</i>. ACM, 2022."
youtube: 
award: 
codeurl: https://github.com/NKNY/bandwagonictir2022
slides: 
---

Optimizing recommender systems based on user interaction data is mainly seen as a problem of dealing with selection bias, where most existing work assumes that interactions from different users are independent. However, it has been shown that in reality user feedback is often influenced by earlier interactions of other users, e.g. via average ratings, number of views or sales per item, etc. This phenomenon is known as the bandwagon effect.

In contrast with previous literature, we argue that the band- wagon effect should not be seen as a problem of statistical bias. In fact, we prove that this effect leaves both individual interactions and their sample mean unbiased. Nevertheless, we show that it can make estimators inconsistent, introducing a distinct set of problems for convergence in relevance estimation. Our theoretical analysis investigates the conditions under which the bandwagon effect poses a consistency problem and explores several approaches for mitigat- ing these issues. This work aims to show that the bandwagon effect poses an underinvestigated open problem that is fundamentally distinct from the well-studied selection bias in recommendation.