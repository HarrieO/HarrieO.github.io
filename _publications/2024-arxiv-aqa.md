---
title: "AQA: Adaptive Question Answering in a Society of LLMs via Contextual Multi-Armed Bandit"
authors: "Mohanna Hoveyda, Arjen P de Vries, Maarten de Rijke, Harrie Oosterhuis, Faegheh Hasibi"
collection: publications
permalink: /publication/2024-arxiv-aqa
excerpt: "We build on recent advances in the orchestration of multiple large language models (LLMs) and formulate adaptive QA as a dynamic orchestration challenge. We define this as a contextual multi-armed bandit problem, where the context is defined by the characteristics of the incoming question and the action space consists of potential communication graph configurations among the LLM agents."
date: 2024-09-20
venue: 'Arxiv preprint'
paperurl: http://harrieo.github.io/files/2024-arxiv-aqa.pdf
citation: "Hoveyda M, de Vries AP, de Rijke M, Oosterhuis H, Hasibi F. AQA: Adaptive question answering in a society of LLMs via contextual multi-armed bandit. arXiv preprint arXiv:2409.13447. 2024 Sep 20."
youtube: 
codeurl: https://github.com/informagi/AQA
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

In question answering (QA), different questions can be effectively addressed with different answering strategies. Some require a simple lookup, while others need complex, multi-step reasoning to be answered adequately. This observation motivates the development of a dynamic method that adaptively selects the most suitable QA strategy for each question, enabling more efficient and effective systems capable of addressing a broader range of question types. To this aim, we build on recent advances in the orchestration of multiple large language models (LLMs) and formulate adaptive QA as a dynamic orchestration challenge. We define this as a contextual multi-armed bandit problem, where the context is defined by the characteristics of the incoming question and the action space consists of potential communication graph configurations among the LLM agents. We then train a linear upper confidence bound model to learn an optimal mapping between different question types and their corresponding optimal multi-LLM communication graph representation. Our experiments show that the proposed solution is viable for adaptive orchestration of a QA system with multiple modules, as it combines the superior performance of more complex strategies while avoiding their costs when simpler strategies suffice.
