---
title: Solving smooth min-min and min-max problems by mixed oracle algorithms
subtitle: ""
publication_types:
  - "1"
authors:
  - Egor Gladin
  - Abdurakhmon Sadiev
  - Alexander Gasnikov
  - Pavel Dvurechensky
  - Aleksandr Beznosikov
  - Mohammad Alkousa
abstract: >
  In this paper we consider two types of problems which have some similarity in
  their structure, namely, min-min problems and min-max saddle-point problems.
  Our approach is based on considering the outer minimization problem as a
  minimization problem with inexact oracle. This inexact oracle is calculated
  via inexact solution of the inner problem, which is either a minimization or a
  maximization problem. Our main assumptions are that the problem is smooth and
  the available oracle is mixed: it is only possible to evaluate the gradient
  w.r.t. the outer block of variables which corresponds to the outer
  minimization problem, whereas for the inner problem only zeroth-order oracle
  is available. To solve the inner problem we use accelerated gradient-free
  method with zeroth-order oracle. To solve the outer problem we use either
  inexact variant of the Vaydya’s cutting-plane method or a variant of
  accelerated gradient method. As a result we propose a framework which leads to
  non- asymptotic complexity bounds for both min-min and min-max problems.
  Moreover, we estimate separately the number of first- and zeroth-order oracle
  calls which are sufficient to reach any desired accuracy.
draft: false
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
featured: false
date: 2021-01-01
publishDate: 2021-02-28T15:24:26.269310Z


links:
url_pdf: https://arxiv.org/pdf/2103.00434.pdf
---
