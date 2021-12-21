---
title: "Unifying Online and Counterfactual Learning to Rank (Extended Abstract)"
authors: "Harrie Oosterhuis and Maarten de Rijke"
collection: publications
permalink: /publication/2021-ijcai-abstract
excerpt: "We propose a novel intervention-aware estimator for both counterfactual and online Learning to Rank (LTR). With the introduction of the intervention-aware estimator, we aim to bridge the online/counterfactual LTR division as it is shown to be highly effective in both online and counterfactual scenarios."
date: 2021-08-21
venue: 'Proceedings of the Thirtieth International Joint Conference on Artificial Intelligence (IJCAI ’21)'
paperurl: http://harrieo.github.io/files/2021-ijcai-abstract.pdf
citation: "H. Oosterhuis and M. de Rijke. &quot;Unifying Online and Counterfactual Learning to Rank (Extended Abstract).&quot; In <i>Proceedings of the Thirtieth International Joint Conference on Artificial Intelligence</i>. International Joint Conferences on Artificial Intelligence, 2021."
youtube: l7kRwcppfFc
codeurl: https://github.com/HarrieO/2021wsdm-unifying-LTR
award: 
slides: /files/slides/2021-wsdm.pdf
poster: /files/posters/2021-wsdm-poster.pdf
---

State-of-the-art Learning to Rank (LTR) methods for optimizing ranking systems based on user interactions are divided into online approaches – that learn by direct interaction – and counterfactual approaches – that learn from historical interactions. We propose a novel intervention-aware estimator to bridge this online/counterfactual division. The estimator corrects for the effect of position bias, trust bias, and item-selection bias by using corrections based on the behavior of the logging policy and on online interventions: changes to the logging policy made during the gathering of click data. Our experimental results show that, unlike existing counterfactual LTR methods, the intervention-aware estimator can greatly benefit from online interventions. To the best of our knowledge, this is the first method that is shown to be highly effective in both online and counterfactual scenarios.

The paper on which this an abstract is based can be found [here](publication/2021-unifying).