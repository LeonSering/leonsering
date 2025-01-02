---
title: ReLU Neural Networks of Polynomial Size for Exact Maximum Flow Computation
authors:
  - Christoph Hertrich
  - Leon Sering
date: "2024-05-25"
publishDate: "2025-01-02T14:31:27.123791Z"
publication_types:
  - article-journal
publication: "*Mathematical Programming*"
doi: https://doi.org/10.1007/s10107-024-02096-x
abstract:
  This paper studies the expressive power of artificial neural networks with
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
