---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Feature learning in shallow neural networks
Neural networks (NNs) have achieved remarkable performance across many domains, but the mechanisms underlying their empirical success are not well understood. A major avenue of research involves understanding how the first few steps of gradient descent leads to feature learning (which is related to early stopping). One way to study this is by analyzing the singular value distributions of the gradients and updated (inner) weight matrix for various parametrizations (see [here](https://arxiv.org/abs/2011.14522)) of two-layer NNs in the proportional scaling regime. This [paper](https://arxiv.org/abs/2205.01445) is a good start to understanding this line of research. Many of the arguments used in this body of work are from high-dimensional probability and random matrix theory.

In the last few months, I have worked with Rishi Sonthalia and Guido Montúfar on a follow-up to [these](https://arxiv.org/abs/2310.07891) [papers](https://arxiv.org/abs/2510.01303). We are studying low-rank structure in the feature matrices of two-layer NNs trained with one large gradient step. Our setting considers a spiked data model where the bulk is allowed to be anisotropic and ill-conditioned, and accommodates regularization in the form of weight decay. To characterize this low-rank behavior, we use *generalized Hermite polynomials* to decompose the feature matrix into a sum of bulk and spike terms. We also establish a *Gaussian equivalence property* for the untrained feature matrix, which makes our eventual investigation of the generalization error more tractable.

