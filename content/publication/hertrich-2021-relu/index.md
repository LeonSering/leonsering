---
title: ReLU Neural Networks of Polynomial Size for Exact Maximum Flow Computation
authors:
- Christoph Hertrich
- Leon Sering
date: '2023-01-01'
publishDate: '2024-02-04T16:35:35.079047Z'
publication_types:
- paper-conference
publication: "*International Conference on Integer Programming and Combinatorial Optimization
  (IPCO '23)*"
doi: 10.1007/978-3-031-32726-1_14
abstract: This paper studies the expressive power of artificial neural networks with
  rectified linear units. In order to study them as a model of real-valued computation,
  we introduce the concept of Max-Affine Arithmetic Programs and show equivalence
  between them and neural networks concerning natural complexity measures. We then
  use this result to show that two fundamental combinatorial optimization problems
  can be solved with polynomial-size neural networks. First, we show that for any
  undirected graph with n nodes, there is a neural network (with fixed weights and
  biases) of size {{< math >}}$O(n^3)${{< /math >}} that takes the edge weights as input and computes the value
  of a minimum spanning tree of the graph. Second, we show that for any directed graph
  with n nodes and m arcs, there is a neural network of size {{< math >}}$O(m^2n^2)${{< /math >}} that takes
  the arc capacities as input and computes a maximum flow. Our results imply that
  these two problems can be solved with strongly polynomial time algorithms that solely
  uses affine transformations and maxima computations, but no comparison-based branchings.
links:
- name: arXiv
  url: https://arxiv.org/abs/2102.06635
---
