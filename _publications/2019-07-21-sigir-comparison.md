---
title: "To Model or to Intervene: A Comparison of Counterfactual and Online Learning to Rank from User Interactions"
authors: "Harrie Oosterhuis, Rolf Jagerman and Maarten de Rijke"
collection: publications
permalink: /publication/2019-comparison
excerpt: "Learning to Rank (LTR) from user interactions is challenging as user feedback often contains high levels of bias and noise. At the moment, two methodologies for dealing with bias prevail in the field of LTR: counterfactual methods that learn from historical data and model user behavior to deal with biases; and online methods that perform interventions to deal with bias but use no explicit user models."
date: 2019-07-21
venue: 'Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR ’19)'
paperurl: http://harrieo.github.io/files/2019-comparison.pdf
citation: "H. Oosterhuis, R. Jagerman, M. de Rijke. &quot;To Model or to Intervene: A Comparison of Counterfactual and Online Learning to Rank from User Interactions.&quot; In <i>Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval</i>. ACM, 2019."
youtube: 
codeurl: https://github.com/rjagerman/sigir2019-user-interactions
othervideo: https://dl.acm.org/action/downloadSupplement?doi=10.1145%2F3331184.3331269&file=cite1-11h40-d1.mp4
tutorialwebsite:
slides:
---

Learning to Rank (LTR) from user interactions is challenging as user feedback often contains high levels of bias and noise. At the moment, two methodologies for dealing with bias prevail in the field of LTR: counterfactual methods that learn from historical data and model user behavior to deal with biases; and online methods that perform interventions to deal with bias but use no explicit user models. For practitioners the decision between either methodology is very important because of its direct impact on end users. Nevertheless, there has never been a direct comparison between these two approaches to unbiased LTR. In this study we provide the first benchmarking of both counterfactual and online LTR methods under different experimental conditions. Our results show that the choice between the methodologies is consequential and depends on the presence of selection bias, and the degree of position bias and interaction noise. In settings with little bias or noise counterfactual methods can obtain the highest ranking performance; however, in other circumstances their optimization can be detrimental to the user experience. Conversely, online methods are very robust to bias and noise but require control over the displayed rankings. Our findings confirm and contradict existing expectations on the impact of model-based and intervention-based methods in LTR, and allow practitioners to make an informed decision between the two methodologies.