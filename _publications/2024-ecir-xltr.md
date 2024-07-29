---
title: "Is Interpretable Machine Learning Effective at Feature Selection for Neural Learning-to-Rank?"
authors: "Lijun Lyu, Nirmal Roy, Harrie Oosterhuis, and Avishek Anand"
collection: publications
permalink: /publication/2024-ecir-xltr
excerpt: "In this work, we explore feature selection for neural learning-to-rank (LTR). In particular, we investigate six widely-used methods from the field of interpretable machine learning (ML) and introduce our own modification, to select the input features that are most important to the ranking behavior."
date: 2024-03-15
venue: 'Proceedings of the 2024 European Conference on Information Retrieval. (ECIR’24)'
paperurl: http://harrieo.github.io/files/2024-ecir-xltr.pdf
citation: "Lyu, L., Roy, N., Oosterhuis, H., & Anand, A. (2024, March). Is Interpretable Machine Learning Effective at Feature Selection for Neural Learning-to-Rank?. In European Conference on Information Retrieval (pp. 384-402). Cham: Springer Nature Switzerland."
youtube: 
codeurl: https://github.com/GarfieldLyu/NeuralFeatureSelectionLTR
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Neural ranking models have become increasingly popular for real-world search and recommendation systems in recent years. Unlike their tree-based counterparts, neural models are much less interpretable. That is, it is very difficult to understand their inner workings and answer questions like how do they make their ranking decisions? or what document features do they find important? This is particularly disadvantageous since interpretability is highly important for real-world systems.

In this work, we explore feature selection for neural learning-to-rank (LTR). In particular, we investigate six widely-used methods from the field of interpretable machine learning (ML) and introduce our own modification, to select the input features that are most important to the ranking behavior. To understand whether these methods are useful for practitioners, we further study whether they contribute to efficiency enhancement. Our experimental results reveal a large feature redundancy in several LTR benchmarks: the local selection method TabNet can achieve optimal ranking performance with less than 10 features; the global methods, particularly our G-L2x, require slightly more selected features, but exhibit higher potential in improving efficiency. We hope that our analysis of these feature selection methods will bring the fields of interpretable ML and LTR closer together.
