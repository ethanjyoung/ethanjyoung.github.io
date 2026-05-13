---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Feature learning in shallow neural networks
Neural networks (NNs) are widely used, but the reasons behind their success are still active areas of research. A major problem is understanding how the first few steps of gradient descent leads to feature learning. One way to study this is by analyzing the singular value distributions of the gradients and updated (inner) weight matrix for various parametrizations (see [here](https://arxiv.org/abs/2011.14522)) of two-layer NNs in the proportional scaling regime. This [paper](https://arxiv.org/abs/2205.01445) is a good start to understanding this line of research. Many of the arguments used in this body of work are from high-dimensional probability and random matrix theory. 

In the last few months, I have worked with Rishi Sonthalia and Guido Montúfar on a follow-up to [these](https://arxiv.org/abs/2310.07891) [papers](https://arxiv.org/abs/2510.01303). We are studying low-rank structure in the feature matrices of two-layer NNs trained with one large gradient step. Our setting considers a spiked data model where the bulk is allowed to be anisotropic and ill-conditioned, and accommodates regularization in the form of weight decay. To characterize this low-rank behavior, we use *generalized Hermite polynomials* to decompose the feature matrix into a sum of bulk and spike terms. We also establish a *Gaussian equivalence property* for the untrained feature matrix, which makes our eventual investigation of the generalization error more tractable.

