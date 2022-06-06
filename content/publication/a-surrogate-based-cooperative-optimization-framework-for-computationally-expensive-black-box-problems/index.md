---
title: A surrogate-based cooperative optimization framework for computationally
  expensive black-box problems
subtitle: ""
publication_types:
  - "2"
authors:
  - José Carlos García-García
  - Ricardo García-Ródenas
  - Esteve Codina
publication_short: Optimization and Engineering, 21 (3), pp. 1053-1093
abstract: "Most parallel surrogate-based optimization algorithms focus only on
  the mechanisms for generating multiple updating points in each cycle, and
  rather less attention has been paid to producing them through the cooperation
  of several algorithms. For this purpose, a surrogate-based cooperative
  optimization framework is here proposed. Firstly, a class of parallel
  surrogate-based optimization algorithms is developed, based on the idea of
  viewing the infill sampling criterion as a bi-objective optimization problem.
  Each algorithm of this class is called a Sequential Multipoint Infill Sampling
  Algorithm (SMISA) and is the combination resulting from choosing a surrogate
  model, an exploitation measure, an exploration measure and a multi-objective
  optimization approach to its solution. SMISAs are the basic algorithms on
  which collaboration mechanisms are established. Many SMISAs can be defined,
  and the focus has been on scalar approaches for bi-objective problems such as
  the ε-constrained method, revisiting the Parallel Constrained Optimization
  using Response Surfaces (CORS-RBF) method and the Efficient Global
  Optimization with Pseudo Expected Improvement (EGO-PEI) algorithm as instances
  of SMISAs. In addition, a parallel version of the Lower Confidence Bound-based
  (LCB) algorithm is given as a member within the SMISA class. Secondly, we
  propose a cooperative optimization framework between the SMISAs. The
  cooperation between SMISAs occurs in two ways: (1) they share solutions and
  their objective function values to update their surrogate models and (2) they
  use the sampled points obtained from different SMISAs to guide their own
  search process. Some convergence results for this cooperative framework are
  given under weak conditions. A numerical comparison between EGO-PEI, Parallel
  CORS-RBF and a cooperative method using both, named CPEI, shows that CPEI
  improves the performance of the baseline algorithms. The numerical results
  were derived from 17 analytic tests and they show the reduction of wall-clock
  time with respect to the increase in the number of processors."
bib_file: ""
url_pdf: https://link.springer.com/article/10.1007/s11081-020-09526-7
url_dataset: ""
url_slides: ""
url_source: ""
url_video: ""
url_project: ""
draft: false
tags: []
categories: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: true
summary: ""
lastmod: 2021-03-13T23:10:02+01:00
publication: "*Optimization and Engineering*"
featured: false
date: 2020-07-02T10:12:35.157Z
publishDate: 2021-03-13T22:09:53.496Z
doi: https://doi.org/10.1007/s11081-020-09526-7
url_code: ""
url_poster: ""
---
