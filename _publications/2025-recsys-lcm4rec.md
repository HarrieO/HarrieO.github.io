---
title: "A Non-Parametric Choice Model That Learns How Users Choose Between Recommended Options"
authors: "Thorsten Krause, Harrie Oosterhuis"
collection: publications
permalink: /publication/2025-recsys-lcm4rec
excerpt: "We propose the learned choice model for recommendation (LCM4Rec), a non-parametric method for estimating the choice model. By applying kernel density estimation, LCM4Rec infers the most likely error distribution that describes the effect of inter-item cannibalization and thereby characterizes the users' choice model."
date: 2025-09-23
venue: 'Proceedings of the 19th ACM Conference on Recommender Systems (RecSys ’25)'
paperurl: http://harrieo.github.io/files/2025-recsys-lcm4rec.pdf
citation: "Krause, T. and Oosterhuis, H., 2025, September. A Non-Parametric Choice Model That Learns How Users Choose Between Recommended Options. In Proceedings of the 19th ACM Conference on Recommender Systems (RecSys ’25). Prague, Czech Republic, 2025."
youtube: 
award: 
codeurl: https://github.com/krauthor/LCM4Rec_RecSys2025
slides: 
---

Choice models predict which items users choose from presented options. In recommendation settings, they can infer user preferences while countering exposure bias. In contrast with traditional univariate recommendation models, choice models consider which competitors appeared with the chosen item. This ability allows them to distinguish whether a user chose an item due to preference, i.e., they liked it; or competition, i.e., it was the best available option. Each choice model assumes specific user behavior, e.g., the multinomial logit model. However, it is currently unclear how accurately these assumptions capture actual user behavior, how wrong assumptions impact inference, and whether better models exist.
In this work, we propose the learned choice model for recommendation (LCM4Rec), a non-parametric method for estimating the choice model. By applying kernel density estimation, LCM4Rec infers the most likely error distribution that describes the effect of inter-item cannibalization and thereby characterizes the users' choice model. Thus, it simultaneously infers what users prefer and how they make choices. Our experimental results indicate that our method (i) can accurately recover the choice model underlying a dataset; (ii) provides robust user preference inference, in contrast with existing choice models that are only effective when their assumptions match user behavior; and (iii) is more resistant against exposure bias than existing choice models. Thereby, we show that learning choice models, instead of assuming them, can produce more robust predictions. We believe this work provides an important step towards better understanding users' choice behavior.