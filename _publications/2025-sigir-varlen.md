---
title: "Learning to Rank with Variable Result Presentation Lengths"
authors: "Norman Knyazev, Harrie Oosterhuis"
collection: publications
permalink: /publication/2025-sigir-varlen
excerpt: "We introduce the variable presentation length ranking task, where simultaneously the ordering of documents and their presentation length is decided. We propose VLPL - a new family of Plackett-Luce list-wise gradient estimation methods for the joint optimization of document ordering and lengths."
date: 2025-07-13
venue: 'Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval. (SIGIR ’25)'
paperurl: http://harrieo.github.io/files/2025-sigir-varlen.pdf
citation: "Knyazev N, Oosterhuis H. (2025, July). Learning to Rank with Variable Result Presentation Lengths. In Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval, Padua, Italy, 2025."
youtube: 
codeurl: https://github.com/NKNY/varlenranksigir2025
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Learning to Rank (LTR) methods generally assume that each document in a top-K ranking is presented in an equal format. However, previous work has shown that users' perceptions of relevance can be changed by varying presentations, i.e., allocating more vertical space to some documents to provide additional textual or image information. Furthermore, presentation length can also redirect attention, as users are more likely to notice longer presentations when scrolling through results. Deciding on the document presentation lengths in a fixed vertical space ranking is an important problem that has not been addressed by existing LTR methods.

We address this gap by introducing the variable presentation length ranking task, where simultaneously the ordering of documents and their presentation length is decided. Despite being a generalization of standard ranking, we show that this setting brings significant new challenges: Firstly, the probability ranking principle no longer applies to this setting, and secondly, the problem cannot be divided into separate ordering and length selection tasks.

We therefore propose VLPL - a new family of Plackett-Luce list-wise gradient estimation methods for the joint optimization of document ordering and lengths. Our semi-synthetic experiments show that VLPL can effectively balance the expected exposure and attractiveness of all documents, achieving the best performance across different ranking settings. Furthermore, we observe that even simple length-aware methods can achieve significant performance improvements over fixed-length models. Altogether, our theoretical and empirical results highlight the importance and difficulties of combining document presentation with LTR.
