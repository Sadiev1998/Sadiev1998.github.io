---
title: Federated Optimization Algorithms with Random Reshuffling and Gradient
  Compression
subtitle: ""
publication_types:
  - "3"
authors:
  - Abdurakhmon Sadiev
  - Grigory Malinovsky
  - Eduard Gorbunov
  - Igor Sokolov
  - Ahmed Khaled
  - Konstantin Burlachenko
  - Peter Richtárik
abstract: Gradient compression is a popular technique for improving
  communication complexity of stochastic first-order methods in distributed
  training of machine learning models. However, the existing works consider only
  with-replacement sampling of stochastic gradients. In contrast, it is
  well-known in practice and recently confirmed in theory that stochastic
  methods based on without-replacement sampling, e.g., Random Reshuffling (RR)
  method, perform better than ones that sample the gradients with-replacement.
  In this work, we close this gap in the literature and provide the first
  analysis of methods with gradient compression and without-replacement
  sampling. We first develop a distributed variant of random reshuffling with
  gradient compression (Q-RR), and show how to reduce the variance coming from
  gradient quantization through the use of control iterates. Next, to have a
  better fit to Federated Learning applications, we incorporate local
  computation and propose a variant of Q-RR called Q-NASTYA. Q-NASTYA uses local
  gradient steps and different local and global stepsizes. Next, we show how to
  reduce compression variance in this setting as well. Finally, we prove the
  convergence results for the proposed methods and outline several settings in
  which they improve upon existing algorithms.
draft: false
url_pdf: https://arxiv.org/pdf/2206.07021.pdf
tags: []
categories: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: ""
lastmod: 2023-03-16T18:24:25+03:00
publication: "*arXiv preprint arXiv:2206.07021*"
featured: false
date: 2022-06-14
publishDate: 2023-03-16T15:24:25.004958Z
---
