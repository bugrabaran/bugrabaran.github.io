---
title: "Closed-form sample probing for learning generative models in zero-shot learning"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper is about improving zero-shot classification with generative modeling'
date: 2022-01-29
venue: 'ICLR 2022'
paperurl: 'https://openreview.net/pdf?id=ljxWpdBl4V'
citation: 'Cetin, S., Baran, O.,B., Cinbiş, R., G., "Closed-form sample probing for learning generative models in zero-shot learning", ICLR 2022'
---

## ABSTRACT
Generative model based approaches have led to significant advances in zero-shot learning (ZSL) over the past few years. These approaches typically aim to learn a conditional generator that synthesizes training samples of classes conditioned on class definitions. The final zero-shot learning model is then obtained by training a supervised classification model over the real and/or synthesized training samples of seen and unseen classes, combined. Therefore, naturally, the generative model needs to produce not only relevant samples, but also those that are sufficiently rich for classifier training purposes, which is handled by various heuristics in existing works. In this paper, we introduce a principled approach for training generative models {\em directly} for training data generation purposes. Our main observation is that the use of closed-form models opens doors to end-to-end training thanks to the differentiability of the solvers. In our approach, at each generative model update step, we fit a task-specific closed-form ZSL model from generated samples, and measure its loss on novel samples all within the compute graph, a procedure that we refer to as {\em sample probing}. In this manner, the generator receives feedback directly based on the value of its samples for model training purposes. Our experimental results show that the proposed sample probing approach improves the ZSL results even when integrated into state-of-the-art generative models.
