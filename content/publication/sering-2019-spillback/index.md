---
title: Nash Flows Over Time with Spillback
authors:
- Leon Sering
- Laura Vargas Koch
date: '2019-01-01'
publishDate: '2024-02-04T16:35:35.007658Z'
publication_types:
- paper-conference
publication: "*ACM-SIAM Symposium on Discrete Algorithms (SODA'19)*"
doi: 10.1137/1.9781611975482.57
abstract: Modeling traffic in road networks is a widely studied but challenging problem, especially 
  under the assumption that drivers act selfishly. A common approach used in simulation software is the deterministic 
  queuing model, for which the structure of dynamic equilibria has been studied extensively in the last couple of years. 
  The basic idea is to model traffic by a continuous flow that travels over time from a source to a sink through a network, 
  in which the arcs are endowed with transit times and capacities. Whenever the flow rate exceeds the capacity a queue 
  builds up and the infinitesimally small flow particles wait in line in front of the bottleneck. Since the queues have 
  no physical dimension, it was not possible, until now, to represent spillback in this model. This was a big drawback, 
  since spillback can be regularly observed in real traffic situations and has a huge impact on travel times in highly 
  congested regions. We extend the deterministic queuing model by introducing a storage capacity that bounds the total 
  amount of flow on each arc. If an arc gets full, the inflow capacity is reduced to the current outflow rate, which 
  can cause queues on previous arcs and blockages of intersections, i.e., spillback. We carry over the main results of 
  the original model to our generalization and characterize dynamic equilibria, called Nash flows over time, by sequences 
  of particular static flows, we call spillback thin flows. Furthermore, we give a constructive proof for the existence 
  of dynamic equilibria, which suggests an algorithm for their computation. This solves an open problem stated by [Koch 
  and Skutella in 2010](https://doi.org/10.1007/s00224-010-9299-y).
links:
- name: arXiv
  url: https://arxiv.org/abs/1807.05862v1
---
