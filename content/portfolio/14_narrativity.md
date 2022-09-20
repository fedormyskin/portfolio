---
date: "2022"
draft: false
image: img/portfolio/14_narrativity.png
showonlyimage: false
title: Computational detection of narrativity
weight: 1
---

Linear regression model to predict the degree of narrativity of short text passages.
<!--more-->

### – 2022 –

with Max Steg and Karlo Slot (University of Groningen, the Netherlands)

![Text passage with highlighted the words that the regression model associates with high (green) and low (red) narrativity][1]

[1]: /img/portfolio/14_narrativity.png

The task of computational textual narrative detection focuses on detecting the presence of narrative parts, or the degree of narrativity in texts. In this work, we focus on detecting the local degree of narrativity in texts, using short text passages. We performed a human annotation experiment on 325 English texts ranging across 20 genres to capture readers' perception by means of three cognitive aspects: suspense, curiosity, and surprise. We then employed a linear regression model to predict narrativity scores for 17,372 texts. When comparing our average annotation scores to similar annotation experiments with different cognitive aspects, we found that Pearson's *r* ranges from .63 to .75. When looking at the calculated narrative probabilities, Pearson's *r* is .91. We found that it is possible to use suspense, curiosity and surprise to detect narrativity. However, there are still differences between methods. This does not imply that there are inherently correct methods, but rather suggests that the underlying definition of narrativity is a determining factor for the results of the computational models employed.

The figure shows the same text passage with highlighted the words that the regression model associates with high (green) and low (red) narrativity. The top passage shows results of the model trained on annotations of textual elements, the bottom passage shows results of the model trained on annotations of reader response.

### Tools and skills

Python, SKlearn, ELI5, Seaborn

Machine learning, regression models, annotation for machine learning


### Outputs

Steg, Max, Karlo Slot, and Federico Pianzola. 2022. Computational Detection of Narrativity: A Comparison Using Textual Features and Reader Response. *LaTeCH-CLfL 2022 - The 6th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature*. 