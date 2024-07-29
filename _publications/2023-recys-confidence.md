---
title: "A Lightweight Method for Modeling Confidence in Recommendations with Learned Beta Distributions"
authors: "Norman Knyazev and Harrie Oosterhuis"
collection: publications
permalink: /publication/2023-recsys-confidence
excerpt: "In this work, we propose learned beta distributions (LBD) as a simple and practical recommendation method with an explicit measure of confidence. Our main insight is that beta distributions predict user preferences as probability distributions that naturally model confidence on a closed interval, yet can be implemented with the minimal model-complexity."
date: 2023-09-14
venue: "Proceedings of the 17th ACM conference on recommender systems (RecSys'23)"
paperurl: http://harrieo.github.io/files/2023-recys-confidence.pdf
citation: "Knyazev, N., & Oosterhuis, H. (2023, September). A lightweight method for modeling confidence in recommendations with learned beta distributions. <i>In Proceedings of the 17th ACM conference on recommender systems (pp. 306-317)</i>."
youtube: 
award: 
codeurl: https://github.com/NKNY/confidencerecsys2023
slides: 
---

Most recommender systems (RecSys) do not provide an indication of confidence in their decisions. Therefore, they do not distinguish between recommendations of which they are certain, and those where they are not. Existing confidence methods for RecSys are either inaccurate heuristics, conceptually complex or computation- ally very expensive. Consequently, real-world RecSys applications rarely adopt these methods, and thus, provide no confidence in- sights in their behavior.
In this work, we propose learned beta distributions (LBD) as a simple and practical recommendation method with an explicit measure of confidence. Our main insight is that beta distributions predict user preferences as probability distributions that naturally model confidence on a closed interval, yet can be implemented with the minimal model-complexity. Our results show that LBD maintains competitive accuracy to existing methods while also having a significantly stronger correlation between its accuracy and confidence. Furthermore, LBD has higher performance when applied to a high-precision targeted recommendation task.
Our work thus shows that confidence in RecSys is possible with- out sacrificing simplicity or accuracy, and without introducing heavy computational complexity. Thereby, we hope it enables bet- ter insight into real-world RecSys and opens the door for novel future applications.