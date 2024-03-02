---
title: 'COMAE: COMprehensive Attribute Exploration for Zero-shot Hashing'
authors:
- Yihang Zhou
- Qingqing Long
- Yuchen Yan
- Xiao Luo
- Zeyu Dong
- Xuezhi Wang
- Zhen Meng
- Pengfei Wang
- Yuanchun Zhou
date: '2024-02-01'
publishDate: '2024-03-02T12:16:26.947694Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Zero-shot hashing (ZSH) has shown excellent success owing to its efficiency
  and generalization in large-scale retrieval scenarios. While considerable success
  has been achieved, there still exist urgent limitations. Existing works ignore the
  locality relationships of representations and attributes, which have effective transferability
  between seeable classes and unseeable classes. Also, the continuous-value attributes
  are not fully harnessed. In response, we conduct a COMprehensive Attribute Exploration
  for ZSH, named COMAE, which depicts the relationships from seen classes to unseen
  ones through three meticulously designed explorations, i.e., point-wise, pair-wise
  and class-wise consistency constraints. By regressing attributes from the proposed
  attribute prototype network, COMAE learns the local features that are relevant to
  the visual attributes. Then COMAE utilizes contrastive learning to comprehensively
  depict the context of attributes, rather than instance-independent optimization.
  Finally, the class-wise constraint is designed to cohesively learn the hash code,
  image representation, and visual attributes more effectively. Experimental results
  on the popular ZSH datasets demonstrate that COMAE outperforms state-of-the-art
  hashing techniques, especially in scenarios with a larger number of unseen label
  classes.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2402.16424
---
