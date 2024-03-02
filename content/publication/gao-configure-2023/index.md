---
title: 'Configure Your Federation: Hierarchical Attention-enhanced Meta-Learning Network
  for Personalized Federated Learning'
authors:
- Yujia Gao
- Pengfei Wang
- Liang Liu
- Chi Zhang
- Huadong Ma
date: '2023-08-01'
publishDate: '2024-03-02T12:16:26.763301Z'
publication_types:
- article-journal
publication: '*ACM Transactions on Intelligent Systems and Technology*'
doi: 10.1145/3591362
abstract: Federated learning, as a distributed machine learning framework, enables
  clients to conduct model training without transmitting their data to the server,
  which is used to solve the dilemma of data silos and data privacy. It can work well
  on clients having similar data characteristics and distribution. However, it has
  some limitations where the dataset of clients may be different in distribution,
  quantity, and concept in many application scenarios. Personalized federated learning
  is a new federated learning paradigm that aims to guarantee client personalized
  models’ effectiveness when collaborating with the cloud server. Intuitively, providing
  further facilitated collaborations for the clients with similar data characteristics
  and distribution can benefit personalized model building. However, due to the invisibility
  of client data, it is challenging to extract client characteristics and define collaborative
  relationships among them from a fine-grained view. Moreover, a reasonable collaborative
  training approach needs to be designed for a distributed server–client framework.
  In this article, we design a Hierarchical Attention-enhanced Meta-learning Network (HAM)
  to address this issue. The main advantage of HAM is that it utilizes the meta-learning
  approach of taking model parameters as features and learns to learn an extra model
  for each client to analyze similarities according to their local dataset automatically.
  According to its two-layers framework, HAM can reasonably achieve a tradeoff between
  clients’ personality and commonality and provides a hybrid model with useful information
  from all clients. Considering there are two networks (HAM and base network) that
  need to learn for each client during the federated training process, we then provide
  an alternative learning approach to train them in an end-to-end fashion. To further
  clarify the approach, we describe the personalized federated learning settings framework
  as FedHAM where the HAM network is distributed deployed in each client. Extensive
  experiments based on two datasets prove that our method outperforms state-of-the-art
  baselines under different evaluation metrics.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3591362
---
