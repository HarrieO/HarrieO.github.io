---
title: "Probabilistic Multileave for Online Retrieval Evaluation"
authors: "Anne Schuth, Robert-Jan Bruintjes, Fritjof Büttner, Joost van Doorn, Carla Groenland, Harrie Oosterhuis, Cong-Nguyen Tran, Bas Veeling, Jos van der Velde, Roger Wechsler, David Woudenberg and Maarten de Rijke"
collection: publications
permalink: /publication/2015-multileave
excerpt: "We propose probabilistic multileave and empirically show that it is highly sensitive and unbiased. An important implication of this result is that historical interactions with multileaved comparisons can be reused, allowing for ranker comparisons that need much less user interaction data."
date: 2015-08-9
venue: 'Proceedings of the 38th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR ’15)'
paperurl: http://harrieo.github.io/files/2015-multileave.pdf
citation: "A. Schuth, R. Bruintjes, F. Büttner, J. van Doorn, C. Groenland, H. Oosterhuis, C. Tran, B. Veeling, J. van der Velde, R. Wechsler, D. Woudenberg, M. de Rijke. &quot;Probabilistic Multileave for Online Retrieval Evaluation.&quot; In <i>Proceedings of the 38th International ACM SIGIR Conference on Research and Development in Information Retrieval</i>. ACM, 2015."
youtube: 
codeurl: https://bitbucket.org/ilps/lerot/src/master/
othervideo:
tutorialwebsite:
slides:
---

Online evaluation methods for information retrieval use implicit signals such as clicks from users to infer preferences between rankers. A highly sensitive way of inferring these preferences is through interleaved comparisons. Recently, interleaved comparisons methods that allow for simultaneous evaluation of more than two rankers have been introduced. These so-called multileaving methods are even more sensitive than their interleaving counterparts. Probabilistic interleaving--whose main selling point is the potential for reuse of historical data--has no multileaving counterpart yet. We propose probabilistic multileave and empirically show that it is highly sensitive and unbiased. An important implication of this result is that historical interactions with multileaved comparisons can be reused, allowing for ranker comparisons that need much less user interaction data. Furthermore, we show that our method, as opposed to earlier sensitive multileaving methods, scales well when the number of rankers increases.