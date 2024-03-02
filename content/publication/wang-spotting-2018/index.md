---
title: 'Spotting Trip Purposes from Taxi Trajectories: A General Probabilistic Model'
authors:
- Pengfei Wang
- Guannan Liu
- Yanjie Fu
- Yuanchun Zhou
- Jianhui Li
date: '2018-05-01'
publishDate: '2024-03-02T12:16:26.532954Z'
publication_types:
- article-journal
publication: '*ACM Transactions on Intelligent Systems and Technology*'
doi: 10.1145/3078849
abstract: What is the purpose of a trip? What are the unique human mobility patterns
  and spatial contexts in or near the pickup points and delivery points of trajectories
  for a specific trip purpose? Many prior studies have modeled human mobility patterns
  in urban regions; however, these analytics mainly focus on interpreting the semantic
  meanings of geographic topics at an aggregate level. Given the lack of information
  about human activities at pick-up and dropoff points, it is challenging to convert
  the prior studies into effective tools for inferring trip purposes. To address this
  challenge, in this article, we study large-scale taxi trajectories from an unsupervised
  perspective in light of the following observations. First, the POI configurations
  of origin and destination regions closely relate to the urban functionality of these
  regions and further indicate various human activities. Second, with respect to the
  functionality of neighborhood environments, trip purposes can be discerned from
  the transitions between regions with different functionality at particular time
  periods.  Along these lines, we develop a general probabilistic framework for spotting
  trip purposes from massive taxi GPS trajectories. Specifically, we first augment
  the origin and destination regions of trajectories by attaching neighborhood POIs.
  Then, we introduce a latent factor, POI Topic , to represent the mixed functionality
  of the regions, such that each origin or destination point in the city can be modeled
  as a mixture over POI Topics. In addition, considering the transitions from origins
  to destinations at specific time periods, the trip time is generated collaboratively
  from the pairwise POI Topics at both ends of the O-D pairs, constituting POI Links
  , and hence the trip purpose can be explained semantically by the POI Links. Finally,
  we present extensive experiments with the real-world data of New York City to demonstrate
  the effectiveness of our proposed method for spotting trip purposes, and moreover,
  the model is validated to perform well in predicting the destinations and trip time
  among all the baseline methods.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3078849
---
