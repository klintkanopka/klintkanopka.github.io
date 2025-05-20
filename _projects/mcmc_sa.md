---
layout: page
title: MCMC Based Short Form Creation
description: A method for developing clinical use short forms using Markov Chain Monte Carlo with simulated annealing
img: assets/img/projects/mcmc_sa.png
importance: 2
category: current
related_publications: false
---

Symptom screeners and patient assessments measure constructs such as health-related quality of life, or levels of mental health symptoms including depressive symptomology or anxiety level. The items are often summarized, through a simple unweighted summed score or through more advanced methods, including factor analysis, Rasch modeling, and item response theory. One consideration that is often overlooked is that screeners are used less for precise measurement of a latent construct but instead for accurate prediction of a diagnosis or expert judgment. As such, we present an alternative method that addresses these concerns through the use of a Markov Chain Monte Carlo algorithm with simulated annealing to explore the search space of short forms coupled with a two-stage loss function that optimizes prediction based upon an unweighted sum score. This method is orders of magnitude more efficient than brute force search and has the advantage of optimizing for prediction of the desired outcome directly, instead of optimizing on the measurement of an intermediate outcome that may not be perfectly aligned with the decision criteria of interest. We apply our method to a screener for alcohol use disorder, demonstrating that under the unweighted sum score scoring constraint, shortened forms can more accurately predict expert judgments than full forms.

Materials:
- [Slides from a talk given at the 2025 International Objective Measurement Workshop](/assets/pdf/slides/mcmc_sa_iomw_slides.pdf)