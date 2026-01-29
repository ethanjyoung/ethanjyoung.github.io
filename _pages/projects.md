---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Feature learning in shallow neural networks
  * Neural networks (NNs) are widely used, but the reasons behind their success are still active areas of research. What I am interested in exploring is how the first few steps of gradient descent leads to feature learning. I have looked at the distributions of singular values in the gradients and updated (inner) weight matrix for various parametrizations (see [here](https://arxiv.org/abs/2011.14522)) of two-layer NNs in the proportional scaling regime. This [paper](https://arxiv.org/abs/2205.01445) is a good start to understanding this line of research. More recently, I began working with Rishi Sonthalia and Guido Montúfar on a follow-up to this [paper](https://arxiv.org/abs/2510.01303). We are studying low-rank structure in the feature matrices of two-layer NNs trained with one large gradient step. To characterize this low-rank behavior, we use what we call generalized Hermite polynomials to decompose the feature matrix into a sum of bulk and spike terms.
