---
layout: page
title: Mixed Subjects Designs
description: Integrating LLM responses into social, behavioral, and measurement research
img: assets/img/projects/mixed_subj_design.png
importance: 1
category: current
related_publications: false
---

Large language models (LLMs) have prompted proposals to replace human subjects in surveys, social science experiments, and psychometric research with simulated responses. Empirical evaluations suggest that this practice (often called _silicon sampling_) is not yet interchangeable with human responses. We study an alternative approach: one in which model-based predictions are used not as substitutes for human data, but as auxiliary measurements within other estimation contexts, including randomized experiments and psychometric calibration studies. This setup, which Broska, Howes, and van Loon refer to as [The Mixed Subjects Design (2025)](https://journals.sagepub.com/doi/full/10.1177/00491241251326865), requires specific care to guarantee unbiasedness when LLM generated responses are only potentially informative. As such, this work focuses on formalizing appropriate estimands for applied mixed-subjects designs and the related software support required for researchers to implement them.

Materials:
- Preprint: [Using large language models as a source of human
behavioral data in social science experiments](https://osf.io/preprints/socarxiv/y74mu_v1)
- [The `mixedsubjects` package in `R`](https://klintkanopka.com/mixedsubjects/)

