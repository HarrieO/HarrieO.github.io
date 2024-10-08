---
title: "Doubly-Robust Estimation for Correcting Position-Bias in Click Feedback for Unbiased Learning to Rank"
authors: "Harrie Oosterhuis"
collection: publications
permalink: /publication/2023-doubly-robust
excerpt: "In this paper, we introduce a novel DR estimator that is the first DR approach specifically designed for position-bias. The difficulty with position bias is that the treatment – user examination – is not directly observable in click data. As a solution, our estimator uses the expected treatment per rank, instead of the actual treatment that existing DR estimators use."
date: 2023-02-07
venue: 'ACM Transactions on Information Systems 41.3 (TOIS ’23)'
paperurl: http://harrieo.github.io/files/2023-doubly-robust.pdf
citation: "H. Oosterhuis. &quot;Doubly-Robust Estimation for Correcting Position-Bias in Click Feedback for Unbiased Learning to Rank.&quot; ACM Transactions on Information Systems 41.3 (2023): 1-33."
youtube: bmhClxLzzxI
codeurl: https://github.com/HarrieO/2022-doubly-robust-LTR
othervideo:
tutorialwebsite: 
slides: https://docs.google.com/presentation/d/e/2PACX-1vTmY6lVQrPOb3TmpNhAIj5FuLXHC6JXCZCdr5eWtX5S3fLkS3T_WmZOP6uCX-Ko7L3VoKvMqh8pPDW-/pub?start=false&loop=false&delayms=3000
googleslidesembed: https://docs.google.com/presentation/d/e/2PACX-1vTmY6lVQrPOb3TmpNhAIj5FuLXHC6JXCZCdr5eWtX5S3fLkS3T_WmZOP6uCX-Ko7L3VoKvMqh8pPDW-/embed?start=false&loop=false&delayms=3000
---


Clicks on rankings suffer from position-bias: generally items on lower ranks are less likely to be examined - and thus clicked - by users, in spite of their actual preferences between items. The prevalent approach to unbiased click-based learning-to-rank (LTR) is based on counterfactual inverse-propensity-scoring (IPS) estimation. In contrast with general reinforcement learning, counterfactual doubly-robust (DR) estimation has not been applied to click-based LTR in previous literature.

In this paper, we introduce a novel DR estimator that is the first DR approach specifically designed for position-bias. The difficulty with position-bias is that the treatment - user examination - is not directly observable in click data. As a solution, our estimator uses the expected treatment per rank, instead of the actual treatment that existing DR estimators use. Our novel DR estimator has more robust unbiasedness conditions than the existing IPS approach, and in addition, provides enormous decreases in variance: our experimental results indicate it requires several orders of magnitude fewer datapoints to converge at optimal performance. For the unbiased LTR field, our DR estimator contributes both increases in state-of-the-art performance and the most robust theoretical guarantees of all known LTR estimators.
