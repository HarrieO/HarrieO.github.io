---
title: "A Deep Generative Recommendation Method for Unbiased Learning from Implicit Feedback"
authors: "Shashank Gupta, Harrie Oosterhuis, and Maarten de Rijke"
collection: publications
permalink: /publication/2023-vae-ips
excerpt: "We introduce an inverse propensity scoring (IPS) based method for training VAEs from implicit feedback data in an unbiased way. Our IPS-based estimator for the VAE training objective, VAE-IPS, is provably unbiased w.r.t. selection bias."
date: 2023-07-18
venue: 'Proceedings of the 2023 ACM SIGIR International Conference on Theory of Information Retrieval 2023. (ICTIR ’23)'
paperurl: http://harrieo.github.io/files/2023-vae-ips.pdf
citation: "Gupta, S., Oosterhuis, H., & de Rijke, M. (2023, August). A Deep Generative Recommendation Method for Unbiased Learning from Implicit Feedback. In Proceedings of the 2023 ACM SIGIR International Conference on Theory of Information Retrieval (pp. 87-93)."
youtube: 
codeurl: https://github.com/shashankg7/VAE-IPS
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Variational autoencoders (VAEs) are the state-of-the-art model for recommendation with implicit feedback signals. Unfortunately, implicit feedback suffers from selection bias, e.g., popularity bias, position bias, etc., and as a result, training from such signals produces
biased recommendation models. Existing methods for debiasing the learning process have not been applied in a generative setting.

We address this gap by introducing an inverse propensity scoring (IPS) based method for training VAEs from implicit feedback data in an unbiased way. Our IPS-based estimator for the VAE training objective, VAE-IPS, is provably unbiased w.r.t. selection bias.
Our experimental results show that the proposed VAE-IPS model reaches significantly higher performance than existing baselines. Our contributions enable practitioners to combine state-of-the-art VAE recommendation techniques with the advantages of bias mitigation for implicit feedback.
