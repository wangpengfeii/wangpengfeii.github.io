---
title: Deep Adaptive Graph Clustering via von Mises-Fisher Distributions
authors:
- Pengfei Wang
- Daqing Wu
- Chong Chen
- Kunpeng Liu
- Yanjie Fu
- Jianqiang Huang
- Yuanchun Zhou
- Jianfeng Zhan
- Xiansheng Hua
date: '2024-05-01'
publishDate: '2024-03-02T12:16:26.754895Z'
publication_types:
- article-journal
publication: '*ACM Transactions on the Web*'
doi: 10.1145/3580521
abstract: Graph clustering has been a hot research topic and is widely used in many
  fields, such as community detection in social networks. Lots of works combining
  auto-encoder and graph neural networks have been applied to clustering tasks by
  utilizing node attributes and graph structure. These works usually assumed the inherent
  parameters (i.e., size and variance) of different clusters in the latent embedding
  space are homogeneous, and hence the assigned probability is monotonous over the
  Euclidean distance between node embeddings and centroids. Unfortunately, this assumption
  usually does not hold since the size and concentration of different clusters can
  be quite different, which limits the clustering accuracy. In addition, the node
  embeddings in deep graph clustering methods are usually L2 normalized so that it
  lies on the surface of a unit hyper-sphere. To solve this problem, we proposed  D  eep  A  daptive  G  raph  C  lustering
  via von Mises-Fisher distributions, namely DAGC. DAGC assumes the node embeddings  H  can
  be drawn from a von Mises-Fisher distribution and each cluster k is associated with
  cluster inherent parameters  ρ   k  which includes cluster center μ and cluster
  cohesion degree κ. Then we adopt an EM-like approach (i.e., 𝒫(  H  textbar  ρ  )
  and 𝒫(  ρ  textbar  H  ), respectively) to learn the embedding and cluster inherent
  parameters alternately. Specifically, with the node embeddings, we proposed to update
  the cluster centers in an attraction-repulsion manner to make the cluster centers
  more separable. And given the cluster inherent parameters, a likelihood-based loss
  is proposed to make node embeddings more concentrated around cluster centers. Thus,
  DAGC can simultaneously improve the intra-cluster compactness and inter-cluster
  heterogeneity. Finally, extensive experiments conducted on four benchmark datasets
  have demonstrated that the proposed DAGC consistently outperforms the state-of-the-art
  methods, especially on imbalanced datasets.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3580521
---
