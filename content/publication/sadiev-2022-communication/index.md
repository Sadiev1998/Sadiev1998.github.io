---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Communication acceleration of local gradient methods via an accelerated primal-dual
  algorithm with inexact prox"
subtitle: ''
summary: ''
authors:
- Abdurakhmon Sadiev
- Dmitry Kovalev 
- Peter Richárik
tags: []
categories: []
date: '2022-07-08'
lastmod: 2023-03-16T18:24:24+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-07-088T15:24:24.841564Z'
publication_types:
- '1'
abstract: 'Inspired by a recent breakthrough of Mishchenko et al (2022), who for the first time showed that local gradient steps can lead to provable communication acceleration, we propose an alternative algorithm which obtains the same communication acceleration as their method (ProxSkip). Our approach is very different, however: it is based on the celebrated method of Chambolle and Pock (2011), with several nontrivial modifications: i) we allow for an inexact computation of the prox operator of a certain smooth strongly convex function via a suitable gradient-based method (e.g., GD, Fast GD or FSFOM), ii) we perform a careful modification of the dual update step in order to retain linear convergence. Our general results offer the new state-of-the-art rates for the class of strongly convex-concave saddle-point problems with bilinear coupling characterized by the absence of smoothness in the dual function. When applied to federated learning, we obtain a theoretically better alternative to ProxSkip: our method requires fewer local steps ( $\mathcal{O}\left(\kappa^{\nicefrac{1}{3}}\right)$ or $\mathcal{O}\left(\kappa^{\nicefrac{1}{4}}\right)$, compared to $\mathcal{O}\left(\kappa^{\nicefrac{1}{2}}\right)$ of ProxSkip), and performs a deterministic number of local steps instead. Like ProxSkip, our method can be applied to optimization over a connected network, and we obtain theoretical improvements here as well.'
publication: ''

tags:
- Source Themes
featured: false

links:
url_pdf: http://arxiv.org/pdf/2207.03957
---
