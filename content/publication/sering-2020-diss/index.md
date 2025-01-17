---
title: Nash Flows Over Time
authors:
- Leon Sering
date: '2020-01-01'
featured: true
publishDate: '2024-02-04T16:35:35.043842Z'
publication_types:
- thesis
doi: 10.14279/depositonce-10640
abstract: Motivated by the dynamic traffic assignment problem and with the goal in
  mind to obtain a better understanding of the complex traffic dynamics, we consider
  a dynamic game in a flow over time model with deterministic queuing in this thesis.
  The dynamic equilibria, called Nash flows over time, in the base version of this
  model were introduced by Koch and Skutella in 2009 and they were already studied
  intensively. But the flow dynamics lack essential features, such as spillback and
  kinematic waves, and more crucially, they can only handle a single commodity. Hence,
  Nash flows over time are only a very rough approximation of a real-world traffic
  scenario. In order to close the gap between large-scale simulation tools, which
  work well in practice but lack any provable foundation, and the mathematical theory,
  we extend this base model by several very natural traffic features and showed that,
  by extending the proof ideas, we can, in most cases, preserve the existence and
  the structural insights of dynamic equilibria. As a first starting point we introduce
  time-dependent capacities and time-dependent speed limits in order to represent
  changes in the road network, such as planned construction work or school zones.
  This extension changes the original model only slightly and it is no surprise that
  it is possible to prove that Nash flows over time in time-dependent networks can,
  again, be constructed by a sequence of static flows, called thin flows, which are
  very similar to the thin flows with resetting of the base model. Much more challenging
  is the consideration of multiple commodities in such a dynamic network game. The
  essential property of a global FIFO principle does not hold for these scenarios,
  and therefore, it is not possible anymore to extend multi-commodity Nash flows over
  time step by step. Instead, we have to consider all infinitesimally small players
  at the same time as the choice of early particles depends not only on all the flow
  already in the network but may also depend on all future flow. Even though we cannot
  use any of the techniques of the base model, we are still able to show the existence
  of dynamic equilibria in this multi-commodity setting with the help of infinite-dimensional
  variational inequalities. Since this was known prior to the work in this thesis,
  the main contribution is the structural insight into these Nash flows over time,
  as we can show that their derivatives have to satisfy a set of conditions similar
  to the thin flow equations. The major difference to the single-commodity case is
  that we cannot consider each thin flow isolated anymore, but instead, we have to
  take into account the flow of the other commodities (the so-called foreign flow),
  and therefore, we have to consider all flow from the past and the future simultaneously.
  Unfortunately, this still does not give a clear instruction on how to construct
  Nash flows over time with multiple commodities, however, for the special case that
  all commodities share the same origin we show that the problem of constructing a
  Nash flow over time reduces to the single-commodity case. The same holds true for
  the other extreme case, that every particle can start at multiple origins but they
  all share a common destination. Clearly, the extension of the base model to a model
  with spillback and kinematic waves is one of the main contributions of this thesis.
  These fundamental traffic features, which are especially relevant in highly congested
  networks, were a huge challenge for the deterministic queuing model. The key idea
  is to restrict the total amount of flow on each arc by an arc specific storage capacity
  and to model the backwards moving gaps between vehicles by a gap flow over time.
  In order to obtain a well-defined flow over time based on the route choices of the
  particles we introduce a priority rule on each intersection. The fair allocation
  condition guarantees that, in the case of spillback, the particles merge according
  to the outflow capacity of each incoming link. As we only consider a single-commodity
  we can, again, use the network-wide FIFO principle in order to construct a Nash
  flow over time in this kinematic wave model. However, most of the proof ideas do
  not transfer to this extension, and therefore, most of the proofs become much more
  involved. In addition, we observe that the arrival times of these dynamic equilibria
  are not unique anymore and that, due to the fact that congestions can block intersections,
  the price of anarchy is unbounded in the spillback model. Finally, we consider a
  different type of flows over time, called instantaneous dynamic equilibria (or IDE
  flow for short). Here, particles do not predict the future evolution, but instead,
  each of them chooses a route depending on the current network configuration, i.e.,
  the current shortest distance to the destination. As these might change drastically
  along the way, each player is allowed to adopt his or her route choice on the way.
  Even though these flows over time do not form a game theoretical Nash equilibrium,
  they are well motivated by real-world scenarios since traffic users, following a
  navigation system, might get re-routed as soon as the current traffic conditions
  change. As we only have to consider the current waiting times it becomes much easier
  to construct such IDE flows. In fact, we can even handle multi-commodity IDE flows
  with the same thin flow technique we use for single-commodity Nash flows over time.
---
