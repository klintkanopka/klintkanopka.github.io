---
layout: page
title: Position Sensitive IRT
description: Development of a mixture item response model to account for item position effects, with estimation software written in PyTorch.
img: assets/img/projects/position_sensitive.png
importance: 1
category: past
related_publications: true
---

Standard item response theory (IRT) models are ill-equipped for when the probability of a correct response depends on the location in the test where an item is encountered—a phenomenon we refer to as position effects. Unmodeled position effects complicate comparing respondents taking the same test. We propose a position-sensitive IRT model that is a mixture of two item response functions, capturing the difference in response probability when the item is encountered early versus late in the test. The mixing proportion depends on item location and latent person-level characteristics, separating person and item contributions to position effects. We present simulation studies outlining various features of model performance and end with an application to a large-scale admissions test with observed position effects.

Materials:
- [Publication in Journal of Educational and Behavioral Statistics](https://journals.sagepub.com/doi/full/10.3102/10769986241289399) {% cite kanopka2024position %}
- [.pdf copy of the paper](/assets/pdf/kanopka-domingue-2024-psirt.pdf)
- [Slides from a talk given to the Fordham Psychometrics Seminar](/assets/pdf/position_sensitive_slides.pdf)

