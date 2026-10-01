---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Feature learning in shallow neural networks
It is widely believed that nonlinear feature learning drives the remarkable performance of neural networks (NNs), but the mechanisms underlying this phenomenon are still not well understood. A line of research has emerged studying how the first step of gradient descent leads to feature learning. In the literature, one often analyzes the singular value distributions of the gradients and updated (inner) weight matrix (see [here](https://arxiv.org/abs/2011.14522)) of two-layer NNs in the proportional scaling regime. This [paper](https://arxiv.org/abs/2205.01445) is a good start to understanding this body of work.

In the last few months, I have worked with Rishi Sonthalia and Guido Montúfar on a follow-up to [these](https://arxiv.org/abs/2310.07891) [papers](https://arxiv.org/abs/2510.01303). We are studying low-rank structure in the feature matrices of two-layer NNs trained with one large gradient step. Our theory accommodates a spiked data model where the bulk is allowed to be anisotropic and ill-conditioned as well as regularization in the form of weight decay. To characterize this low-rank behavior, we use Wick products and generalized Hermite polynomials to decompose the feature matrix into a sum of bulk and spike terms. Importantly, we show that as we increase the step size, the number of potential spikes increases combinatorially. We also establish a Gaussian equivalence property for the untrained feature matrix, which allows us to derive a staircase property for the generalization error.

