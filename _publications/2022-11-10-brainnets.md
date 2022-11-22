---
title: "Comparing Shallow and Deep Graph Models for Brain Network Analysis"
collection: publications
permalink:
excerpt: 'We benchmark the classification performance of graph kernel SVM and GNNs on neuroimaging data.'
date: 2022-11-10
venue: 'BrainNN2022 at IEEE Big Data (to appear)'
paperurl:
citation:
---

_Joint with Erica Choi and Sally Smith; mentored by Dr. Carl Yang_

_**Abstract**_: It is well-established that graph neural networks (GNNs) can effectively model networked data in a variety of fields. However, whether GNNs can outperform traditional shallow graph classification models such as graph kernels for brain network analysis remains unclear. To this end, we analyze different approaches for modeling brain networks, including graph kernel based SVM, basic GNNs and kernelized GNNs. These models are designed to aid in the analysis of diseases and mental disorders such as bipolar disorder, human immunodeficiency virus (HIV), post-traumatic stress disorder (PTSD), and depression. In particular, we conduct experiments with three methods: kernelized support vector machines (SVM), message passing graph neural networks (MPGNNs), and kernel graph neural networks (KerGNN). We conclude that 1) deep models (GNNs) generally outperform shallow models (SVM) and 2) models considering specific graph motifs do not seem to significantly improve performance. We also identify other graph kernels and GNN frameworks that show promise in motivating further research in brain network analysis.
