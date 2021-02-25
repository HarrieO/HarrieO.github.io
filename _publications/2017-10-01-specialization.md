---
title: "Query-level Ranker Specialization"
authors: "Rolf Jagerman, Harrie Oosterhuis and Maarten de Rijke"
collection: publications
permalink: /publication/2017-specialization
excerpt: "Traditional Learning to Rank models optimize a single ranking function for all available queries. This assumes that all queries come from a homogenous source. Instead, it seems reasonable to assume that queries originate from heterogenous sources, where certain queries may require documents to be ranked differently."
date: 2017-10-01
venue: 'Proceedings of the 1st International Workshop on LEARning Next gEneration Rankers, co-located with the 3rd ACM International Conference on the Theory of Information Retrieval (ICTIR ’17)'
paperurl: http://harrieo.github.io/files/2017-specialization.pdf
citation: "R. Jagerman, H. Oosterhuis, M. de Rijke. &quot;Query-level Ranker Specialization.&quot; In <i>Proceedings of the 1st International Workshop on LEARning Next gEneration Rankers, co-located with the 3rd ACM International Conference on the Theory of Information Retrieval (ICTIR ’2017).</i>. ACM, 2017."
youtube: 
codeurl:
othervideo:
tutorialwebsite:
slides:
---

Traditional Learning to Rank models optimize a single ranking function for all available queries. This assumes that all queries come from a homogenous source. Instead, it seems reasonable to assume that queries originate from heterogenous sources, where certain queries may require documents to be ranked differently. We introduce the Specialized Ranker Model which assigns queries to different rankers that become specialized on a subset of the available queries. We provide a theoretical foundation for this model starting from the listwise Plackett-Luce ranking model and derive a computationally feasible expectation-maximization procedure to infer the model's parameters. Furthermore we experiment using a noisy oracle to model the risk/reward tradeoff that exists when deciding which specialized ranker to use for unseen queries.