---
layout: page
title: Measurement Induced Confounding
description: Estimating causal effects with latent confounding variables
img: assets/img/projects/measurement_induced_confounding.png
importance: 3
category: current
related_publications: false
---

A critical assumption of observational studies is that all confounding variables must be known and sufficiently adjusted for to estimate causal effects. An implicit, and often overlooked, aspect of this assumption is that all confounding variables have been measured without error. In the social and medical sciences, latent traits such as motivation, self-efficacy, and ability measures are likely confounding variables. Because latent traits are not directly observable, conventional approaches to adjust for them in observational studies rely on collecting responses to individual items on a test or survey instrument and then adjust for sum scores, measurement model-derived ability estimates, or item responses directly. Through a process we describe as measurement induced confounding, we show that measurement error propagates through the estimation process and that current conventional approaches to adjusting for latent traits in observational studies produce biased estimates of the average treatment effect with incorrectly calibrated coverage properties. A critical implication of this finding is that current observational studies that attempt to adjust for latent confounding variables likely put forth biased causal estimates with incorrect uncertainty intervals. We show that measurement induced confounding can be resolved through a Bayesian Joint Estimation approach that simultaneously estimates the measurement model, the treatment assignment model, and the response model.

Materials:
- Preprint: [Measurement Induced Confounding](https://arxiv.org/abs/2606.28774)