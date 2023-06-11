---
title: Adaptive Compression for Communication-Efficient Distributed Training
subtitle: ""
publication_types:
  - "3"
authors:
  - Maksim Makarenko
  - Elnur Gasanov
  - Rustem Islamov
  - Abdurakhmon Sadiev
  - Peter Richtárik
abstract: We propose Adaptive Compressed Gradient Descent (AdaCGD) - a novel
  optimization algorithm for communication-efficient training of supervised
  machine learning models with adaptive compression level. Our approach is
  inspired by the recently proposed three point compressor (3PC) framework of
  Richtarik et al. (2022), which includes error feedback (EF21), lazily
  aggregated gradient (LAG), and their combination as special cases, and offers
  the current state-of-the-art rates for these methods under weak assumptions.
  While the above mechanisms offer a fixed compression level, or adapt between
  two extremes only, our proposal is to perform a much finer adaptation. In
  particular, we allow the user to choose any number of arbitrarily chosen
  contractive compression mechanisms, such as Top-K sparsification with a
  user-defined selection of sparsification levels K, or quantization with a
  user-defined selection of quantization levels, or their combination. AdaCGD
  chooses the appropriate compressor and compression level adaptively during the
  optimization process. Besides i) proposing a theoretically-grounded
  multi-adaptive communication compression mechanism, we further ii) extend the
  3PC framework to bidirectional compression, i.e., we allow the server to
  compress as well, and iii) provide sharp convergence bounds in the strongly
  convex, convex and nonconvex settings. The convex regime results are new even
  for several key special cases of our general mechanism, including 3PC and
  EF21. In all regimes, our rates are superior compared to all existing adaptive
  compression methods.
draft: false
tags: []
categories: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: ""
lastmod: 2023-03-16T18:24:24+03:00
publication: "*arXiv preprint arXiv:2211.00188*"
featured: false
date: 2022-01-01
publishDate: 2022-10-31T15:24:24.680833Z
---

links:
url_pdf: https://arxiv.org/pdf/2211.00188.pdf
