---
title: "Reliable Confidence Intervals for Information Retrieval Evaluation Using Generative A.I."
authors: "Harrie Oosterhuis, Rolf Jagerman, Zhen Qin, Xuanhui Wang, and Michael Bendersky"
collection: publications
permalink: /publication/2024-kdd-reliable-genAI
excerpt: "Recent advancements in generative artificial intelligence -specifically large language models (LLMs)- can generate relevance annotations at an enormous scale with relatively small computational costs. Potentially, this could alleviate the costs traditionally associated with IR evaluation and make it applicable to numerous low-resource applications. However, generated relevance annotations are not immune to (systematic) errors, and as a result, directly using them for evaluation produces unreliable results."
date: 2024-08-26
venue: 'Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ’24).'
paperurl: http://harrieo.github.io/files/2024-kdd-reliable-genAI.pdf
citation: "Oosterhuis, H., Jagerman, R., Qin, Z., Wang, X., & Bendersky, M. (2024). Reliable Confidence Intervals for Information Retrieval Evaluation Using Generative AI. Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ’24), August 25–29, 2024, Barcelona, Spain. ACM, New York, NY, USA, 11 pages."
youtube: 
codeurl: https://github.com/google-research/google-research/tree/master/high_confidence_ir_eval_using_genai
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

The traditional evaluation of information retrieval (IR) systems is generally very costly as it requires manual relevance annotation from human experts. Recent advancements in generative artificial intelligence -specifically large language models (LLMs)- can generate relevance annotations at an enormous scale with relatively small computational costs. Potentially, this could alleviate the costs traditionally associated with IR evaluation and make it applicable to numerous low-resource applications. However, generated relevance annotations are not immune to (systematic) errors, and as a result, directly using them for evaluation produces unreliable results. In this work, we propose two methods based on prediction-powered inference and conformal risk control that utilize computer-generated relevance annotations to place reliable confidence intervals (CIs) around IR evaluation metrics. Our proposed methods require a small number of reliable annotations from which the methods can statistically analyze the errors in the generated annotations. Using this information, we can place CIs around evaluation metrics with strong theoretical guarantees. Unlike existing approaches, our conformal risk control method is specifically designed for ranking metrics and can vary its CIs per query and document. Our experimental results show that our CIs accurately capture both the variance and bias in evaluation based on LLM annotations, better than the typical empirical bootstrapping estimates. We hope our contributions bring reliable evaluation to the many IR applications where this was traditionally infeasible.
