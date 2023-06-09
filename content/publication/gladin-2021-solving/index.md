---
title: Solving smooth min-min and min-max problems by mixed oracle algorithms
subtitle: ""
authors:
  - Egor Gladin
  - Abdurakhmon Sadiev
  - Alexander Gasnikov
  - Pavel Dvurechensky
  - Aleksandr Beznosikov
  - Mohammad Alkousa
abstract: "In this paper, we consider two types of problems that have some
  similarity in their structure, namely, min-min problems and min-max
  saddle-point problems. Our approach is based on considering the outer
  minimization problem as a minimization problem with an inexact oracle. This
  inexact oracle is calculated via an inexact solution of the inner problem,
  which is either minimization or maximization problem. Our main assumption is
  that the available oracle is mixed: it is only possible to evaluate the
  gradient w.r.t. the outer block of variables which corresponds to the outer
  minimization problem, whereas for the inner problem, only zeroth-order oracle
  is available. To solve the inner problem, we use the accelerated gradient-free
  method with zeroth-order oracle. To solve the outer problem, we use either an
  inexact variant of Vaidya’s cutting-plane method or a variant of the
  accelerated gradient method. As a result, we propose a framework that leads to
  non-asymptotic complexity bounds for both min-min and min-max problems.
  Moreover, we estimate separately the number of first- and zeroth-order oracle
  calls, which are sufficient to reach any desired accuracy."
draft: false
url_pdf: https://arxiv.org/pdf/2103.00434.pdf
publication_types:
  - "1"
featured: false
tags: []
categories: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: ""
lastmod: 2023-03-16T18:24:26+03:00
publication: "*Mathematical Optimization Theory and Operations Research: Recent
  Trends: 20th International Conference, MOTOR 2021, Irkutsk, Russia, July
  5--10, 2021, Revised Selected Papers 20*"
date: 2021-02-28
publishDate: 2021-02-28
---
