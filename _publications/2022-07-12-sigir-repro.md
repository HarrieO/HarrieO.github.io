---
title: "State Encoders in Reinforcement Learning for Recommendation: A Reproducibility Study"
authors: "Jin Huang, Harrie Oosterhuis, Bunyamin Cetinkaya, Thijs Rood and Maarten de Rijke"
collection: publications
permalink: /publication/2022-sigir-repro
excerpt: "We reproduce and expand on the existing comparison of attention-based state encoders (1) in the publicly available debiased RL4Rec SOFA simulator with (2) a different RL method, (3) more state encoders, and (4) a different dataset."
date: 2022-07-12
venue: 'Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR ’22)'
paperurl: http://harrieo.github.io/files/2022-sigir-repro.pdf
citation: "J. Huang, H. Oosterhuis, B. Cetinkaya, T. Rood and M. de Rijke. &quot;State Encoders in Reinforcement Learning for Recommendation: A Reproducibility Study.&quot; In <i>Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval</i>. ACM, 2022."
youtube: 
codeurl: https://github.com/BetsyHJ/RL4Rec
othervideo:
tutorialwebsite: 
slides: 
---

Methods for reinforcement learning for recommendation (RL4Rec) are increasingly receiving attention as they can quickly adapt to user feedback. A typical RL4Rec framework consists of (1) a state encoder to encode the state that stores the users’ historical interactions, and (2) an RL method to take actions and observe rewards. Prior work compared four state encoders in an environment where user feedback is simulated based on real-world logged user data. An attention-based state encoder was found to be the optimal choice as it reached the highest performance. However, this finding is limited to the actor-critic method, four state encoders, and evaluation-simulators that do not debias logged user data. In response to these shortcomings, we reproduce and expand on the existing compari- son of attention-based state encoders (1) in the publicly available debiased RL4Rec SOFA simulator with (2) a different RL method, (3) more state encoders, and (4) a different dataset. Importantly, our experimental results indicate that existing findings do not generalize to the debiased SOFA simulator generated from a different dataset and a Deep Q-Network (DQN)-based method when compared with more state encoders.