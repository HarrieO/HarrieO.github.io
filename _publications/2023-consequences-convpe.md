---
title: "A First Look at Selection Bias in Preference Elicitation for Recommendation"
authors: "Shashank Gupta, Harrie Oosterhuis, and Maarten de Rijke"
collection: publications
permalink: /publication/2023-consequences-convpe
excerpt: "We take a first look at the effects of selection bias in preference elicitation and how they may be further investigated in the future. We find that a big hurdle is the current lack of any publicly available dataset that has preference elicitation interactions."
date: 2023-09-18
venue: 'CONSEQUENCES Workshop at RecSys ’23. (CONSEQUENCES ’23)'
paperurl: http://harrieo.github.io/files/2023-consequences-convpe.pdf
citation: "Shashank Gupta, Harrie Oosterhuis, and Maarten de Rijke. 2023. A First Look at Selection Bias in Preference Elicitation for Recommendation. In CONSEQUENCES Workshop at RecSys ’23, September 18-22, 2023, Singapore."
youtube: 
codeurl: https://github.com/shashankg7/Bias-Preference-Elicitation
othervideo:
tutorialwebsite: 
slides: 
googleslidesembed: 
---

Preference elicitation explicitly asks users what kind of recommendations they would like to receive. It is a popular technique for conversational recommender systems to deal with cold-starts. Previous work has studied selection bias in implicit feedback, e.g., clicks, and in some forms of explicit feedback, i.e., ratings on items. Despite the fact that the extreme sparsity of preference elicitation interactions make them severely more prone to selection bias than natural interactions, the effect of selection bias in preference elicitation on the resulting recommendations has not been studied yet. To address this gap, we take a first look at the effects of selection bias in preference elicitation and how they may be further investigated in the future. We find that a big hurdle is the current lack of any publicly available dataset that has preference elicitation interactions. As a solution, we propose a simulation of a topic-based preference elicitation process. The results from our simulation-based experiments indicate (i) that ignoring the effect of selection bias early in preference elicitation can lead to an exacerbation of overrepresentation in subsequent item recommendations, and (ii) that debiasing methods can alleviate this effect, which leads to significant improvements in subsequent item recommendation performance.
Our aim is for the proposed simulator and initial results to provide a starting point and motivation for future research into this important but overlooked problem setting.
