---
title: "Local Feature Selection without Label or Feature Leakage for Interpretable Machine Learning Predictions"
authors: "Harrie Oosterhuis, Lijun Lyu, and Avishek Anand"
collection: publications
permalink: /publication/2024-icml-featselect
excerpt: "Local feature selection in machine learning provides instance-specific explanations by focusing on the most relevant features for each prediction, enhancing the interpretability of complex models. However, such methods tend to produce misleading explanations by encoding additional information in their selections."
date: 2024-07-23
venue: 'Proceedings of the 41st International Conference on Machine Learning, Vienna, Austria. PMLR 235, 2024. (ICML’24)'
paperurl: http://harrieo.github.io/files/2024-icml-featselect.pdf
citation: "Oosterhuis, H., Lyu, L., & Anand, A. (2024). Local Feature Selection without Label or Feature Leakage for Interpretable Machine Learning Predictions. In Proceedings of the 41st International Conference on Machine Learning, Vienna, Austria. PMLR 235, 2024."
youtube: 
codeurl: https://github.com/GarfieldLyu/SUWR
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Local feature selection in machine learning provides instance-specific explanations by focusing on the most relevant features for each prediction, enhancing the interpretability of complex models. However, such methods tend to produce misleading explanations by encoding additional information in their selections. In this work, we attribute the problem of misleading selections by formalizing the concepts of label and feature leakage. We rigorously derive the necessary and sufficient conditions under which we can guarantee no leakage, and show existing methods do not meet these conditions. Furthermore, we propose the first local feature selection method that is proven to have no leakage called SUWR. Our experimental results indicate that SUWR is less prone to overfitting and combines state-of-the-art predictive performance with high feature-selection sparsity. Our generic and easily extendable formal approach provides a strong theoretical basis for future work on interpretability with reliable explanations.
