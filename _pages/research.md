---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Feature learning
It is widely believed that nonlinear feature learning drives the remarkable performance of neural networks (NNs), but the mechanisms underlying this phenomenon are still not well understood. A line of research has emerged studying how the first step of gradient descent leads to feature learning. In the literature, one often analyzes the singular value distributions of the gradients and updated (inner) weight matrix (see [here](https://arxiv.org/abs/2011.14522)) of two-layer NNs in the proportional scaling regime. This [paper](https://arxiv.org/abs/2205.01445) is a good start to understanding this body of work.

My recent work with Rishi Sonthalia and Guido Montúfar studies low-rank structure in the feature matrices of two-layer NNs trained with one large gradient step. Our theory accommodates a spiked data model where the bulk is allowed to be anisotropic and ill-conditioned as well as weight decay. To characterize this low-rank behavior, we use generalized Hermite polynomials to decompose the feature matrix into a sum of bulk and spike terms. We also establish a Gaussian equivalence property for the untrained features, which makes the generalization error analytically tractable.

## Curriculum learning
Recently, I have started thinking about how to identify phase transitions in curriculum learning under a self-play environment.
