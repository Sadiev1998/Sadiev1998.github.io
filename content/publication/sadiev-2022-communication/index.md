---
title: Communication acceleration of local gradient methods via an accelerated
  primal-dual algorithm with inexact prox
subtitle: ""
authors:
  - Abdurakhmon Sadiev
  - Dmitry Kovalev
  - Peter Richárik
abstract: >
  Inspired by a recent breakthrough of Mishchenko et al (2022), who for the
  first time showed that local gradient steps can lead to provable communication
  acceleration, we propose an alternative algorithm which obtains the same
  communication acceleration as their method (ProxSkip). Our approach is very
  different, however: it is based on the celebrated method of Chambolle and Pock
  (2011), with several nontrivial modifications: i) we allow for an inexact
  computation of the prox operator of a certain smooth strongly convex function
  via a suitable gradient-based method (e.g., GD, Fast GD or FSFOM), ii) we
  perform a careful modification of the dual update step in order to retain
  linear convergence. Our general results offer the new state-of-the-art rates
  for the class of strongly convex-concave saddle-point problems with bilinear
  coupling characterized by the absence of smoothness in the dual function. When
  applied to federated learning, we obtain a theoretically better alternative to
  ProxSkip: our method requires fewer local steps ( O(κ1/3) or O(κ1/4), compared
  to  O(κ1/2) of ProxSkip), and performs a deterministic number of local steps
  instead. Like ProxSkip, our method can be applied to optimization over a
  connected network, and we obtain theoretical improvements here as well.
draft: false
url_pdf: http://arxiv.org/pdf/2207.03957
publication_types:
  - "1"
featured: false
tags: []
categories: []
summary: ""
lastmod: 2023-03-16T18:24:26+03:00
publication: "* Advances in Neural Information Processing Systems 35 (NeurIPS 2022)*"
date: 2021-07-08
links: null
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
publishDate: 2021-02-28T15:24:26.269Z
---
