---
title: 'Unveiling Delay Effects in Traffic Forecasting: A Perspective from Spatial-Temporal
  Delay Differential Equations'
authors:
- Qingqing Long
- Zheng Fang
- Chen Fang
- Chong Chen
- Pengfei Wang
- Yuanchun Zhou
date: '2024-02-01'
publishDate: '2024-03-02T12:16:26.970596Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: "Traffic flow forecasting is a fundamental research issue for transportation
  planning and management, which serves as a canonical and typical example of spatial-temporal
  predictions. In recent years, Graph Neural Networks (GNNs) and Recurrent Neural
  Networks (RNNs) have achieved great success in capturing spatial-temporal correlations
  for traffic flow forecasting. Yet, two non-ignorable issues haven't been well solved:
  1) The message passing in GNNs is immediate, while in reality the spatial message
  interactions among neighboring nodes can be delayed. The change of traffic flow
  at one node will take several minutes, i.e., time delay, to influence its connected
  neighbors. 2) Traffic conditions undergo continuous changes. The prediction frequency
  for traffic flow forecasting may vary based on specific scenario requirements. Most
  existing discretized models require retraining for each prediction horizon, restricting
  their applicability. To tackle the above issues, we propose a neural Spatial-Temporal
  Delay Differential Equation model, namely STDDE. It includes both delay effects
  and continuity into a unified delay differential equation framework, which explicitly
  models the time delay in spatial information propagation. Furthermore, theoretical
  proofs are provided to show its stability. Then we design a learnable traffic-graph
  time-delay estimator, which utilizes the continuity of the hidden states to achieve
  the gradient backward process. Finally, we propose a continuous output module, allowing
  us to accurately predict traffic flow at various frequencies, which provides more
  flexibility and adaptability to different scenarios. Extensive experiments show
  the superiority of the proposed STDDE along with competitive computational efficiency."
tags:
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2402.01231
---
