---
title: Graph Soft-Contrastive Learning via Neighborhood Ranking
authors:
- Zhiyuan Ning
- Pengfei Wang
- Pengyang Wang
- Ziyue Qiao
- Wei Fan
- Denghui Zhang
- Yi Du
- Yuanchun Zhou
date: '2023-08-01'
publishDate: '2024-03-02T12:16:26.904797Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: "Graph Contrastive Learning (GCL) has emerged as a promising approach in
  the realm of graph self-supervised learning. Prevailing GCL methods mainly derive
  from the principles of contrastive learning in the field of computer vision: modeling
  invariance by specifying absolutely similar pairs. However, when applied to graph
  data, this paradigm encounters two significant limitations: (1) the validity of
  the generated views cannot be guaranteed: graph perturbation may produce invalid
  views against semantics and intrinsic topology of graph data; (2) specifying absolutely
  similar pairs in the graph views is unreliable: for abstract and non-Euclidean graph
  data, it is difficult for humans to decide the absolute similarity and dissimilarity
  intuitively. Despite the notable performance of current GCL methods, these challenges
  necessitate a reevaluation: Could GCL be more effectively tailored to the intrinsic
  properties of graphs, rather than merely adopting principles from computer vision?
  In response to this query, we propose a novel paradigm, Graph Soft-Contrastive Learning
  (GSCL). This approach facilitates GCL via neighborhood ranking, avoiding the need
  to specify absolutely similar pairs. GSCL leverages the underlying graph characteristic
  of diminishing label consistency, asserting that nodes that are closer in the graph
  are overall more similar than far-distant nodes. Within the GSCL framework, we introduce
  pairwise and listwise gated ranking InfoNCE loss functions to effectively preserve
  the relative similarity ranking within neighborhoods. Moreover, as the neighborhood
  size exponentially expands with more hops considered, we propose neighborhood sampling
  strategies to improve learning efficiency. Our extensive empirical results across
  11 commonly used graph datasets-including 8 homophily graphs and 3 heterophily graphs-demonstrate
  GSCL's superior performance compared to 20 SOTA GCL methods."
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2209.13964
---
