---
title: Boosting Urban Traffic Speed Prediction via Integrating Implicit Spatial Correlations
authors:
- Dongkun Wang
- Wei Fan
- Pengyang Wang
- Pengfei Wang
- Dongjie Wang
- Denghui Zhang
- Yanjie Fu
date: '2022-12-01'
publishDate: '2024-03-02T12:16:27.028740Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Urban traffic speed prediction aims to estimate the future traffic speed
  for improving the urban transportation services. Enormous efforts have been made
  on exploiting spatial correlations and temporal dependencies of traffic speed evolving
  patterns by leveraging explicit spatial relations (geographical proximity) through
  pre-defined geographical structures (it e.g., region grids or road networks). While
  achieving promising results, current traffic speed prediction methods still suffer
  from ignoring implicit spatial correlations (interactions), which cannot be captured
  by grid/graph convolutions. To tackle the challenge, we propose a generic model
  for enabling the current traffic speed prediction methods to preserve implicit spatial
  correlations. Specifically, we first develop a Dual-Transformer architecture, including
  a Spatial Transformer and a Temporal Transformer. The Spatial Transformer automatically
  learns the implicit spatial correlations across the road segments beyond the boundary
  of geographical structures, while the Temporal Transformer aims to capture the dynamic
  changing patterns of the implicit spatial correlations. Then, to further integrate
  both explicit and implicit spatial correlations, we propose a distillation-style
  learning framework, in which the existing traffic speed prediction methods are considered
  as the teacher model, and the proposed Dual-Transformer architectures are considered
  as the student model. The extensive experiments over three real-world datasets indicate
  significant improvements of our proposed framework over the existing methods.
tags:
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2212.12932
---
