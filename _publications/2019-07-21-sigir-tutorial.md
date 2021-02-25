---
title: "Optimizing Ranking Models in an Online Setting"
authors: "Harrie Oosterhuis and Maarten de Rijke"
collection: publications
permalink: /publication/2019-oltr-comparison
excerpt: "In this paper, we investigate whether the previous conclusions about the PDGD and DBGD comparison generalize from ideal to worst-case circumstances. We do so in two ways. First, we compare the theoretical properties of PDGD and DBGD, by taking a critical look at previously proven properties in the context of ranking. Second, we estimate an upper and lower bound on the performance of methods by simulating both ideal user behavior and extremely difficult behavior, i.e., almost-random non-cascading user models."
date: 2019-07-21
venue: 'Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR ’19)'
paperurl: http://harrieo.github.io/files/2019-oltr-comparison.pdf
citation: "H. Oosterhuis, R. Jagerman, M. de Rijke. &quot;To Model or to Intervene: A Comparison of Counterfactual and Online Learning to Rank from User Interactions.&quot; In <i>Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval</i>. ACM, 2019."
youtube: 
codeurl: https://github.com/rjagerman/sigir2019-user-interactions
othervideo: http://harrieo.github.io/files/2019-comparison.mp4
tutorialwebsite:
slides:
---

Online Learning to Rank (OLTR) methods optimize ranking models by directly interacting with users, which allows them to be very efficient and responsive. All OLTR methods introduced during the past decade have extended on the original OLTR method: Dueling Bandit Gradient Descent (DBGD). Recently, a fundamentally different approach was introduced with the Pairwise Differentiable Gradient Descent (PDGD) algorithm. To date the only comparisons of the two approaches are limited to simulations with cascading click models and low levels of noise. The main outcome so far is that PDGD converges at higher levels of performance and learns considerably faster than DBGD-based methods. However, the PDGD algorithm assumes cascading user behavior, potentially giving it an unfair advantage. Furthermore, the robustness of both methods to high levels of noise has not been investigated. Therefore, it is unclear whether the reported advantages of PDGD over DBGD generalize to different experimental conditions. In this paper, we investigate whether the previous conclusions about the PDGD and DBGD comparison generalize from ideal to worst-case circumstances. We do so in two ways. First, we compare the theoretical properties of PDGD and DBGD, by taking a critical look at previously proven properties in the context of ranking. Second, we estimate an upper and lower bound on the performance of methods by simulating both ideal user behavior and extremely difficult behavior, i.e., almost-random non-cascading user models. Our findings show that the theoretical bounds of DBGD do not apply to any common ranking model and, furthermore, that the performance of DBGD is substantially worse than PDGD in both ideal and worst-case circumstances. These results reproduce previously published findings about the relative performance of PDGD vs. DBGD and generalize them to extremely noisy and non-cascading circumstances.