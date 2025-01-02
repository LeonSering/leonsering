---
title: RapidSolve
summary: A Rust library for solving optimization problems with local-search based meta-heuristics.
tags:
  - Major
  - Optimization
date: "2024-07-01T00:00:00Z"
# Optional external URL for project (replaces project detail page).
# external_link: ''

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/LeonSering/rapid_solve
  - name: Doc
    icon: rust
    icon_pack: fab
    url: https://docs.rs/rapid_solve/
  - name: Crate
    url: https://crates.io/crates/rapid_solve
---

During my time at ETH Zürich, I gained extensive experience in solving optimization problems using
local search-based meta-heuristics. What started as a hobby project evolved into a Rust library
called [RapidSolve](https://docs.rs/rapid_solve), which provides a framework for implementing
multiple meta-heuristics to tackle combinatorial optimization problems. Over time, I developed and
integrated the following algorithms into the library:

- [(Parallel/recursive) local search](https://docs.rs/rapid_solve/latest/rapid_solve/heuristics/local_search)
- [Threshold accepting](https://docs.rs/rapid_solve/latest/rapid_solve/heuristics/threshold_accepting)
- [Simulated annealing](https://docs.rs/rapid_solve/latest/rapid_solve/heuristics/simulated_annealing)
- [(Parallel) tabu search](https://docs.rs/rapid_solve/latest/rapid_solve/heuristics/tabu_search)

The library is designed to be highly extensible, and I plan to incorporate additional algorithms in
the future.

One of RapidSolve's standout features is its support for hierarchical objectives, allowing the
meta-heuristics to address problems in multiple stages automatically. For example, if the primary
objective is to minimize a violation penalty, the meta-heuristic first seeks a feasible solution
(eliminating violations) before optimizing the remaining objectives.

Before releasing the library on [crates.io](https://crates.io/crates/rapid_solve),
I added comprehensive documentation including example code demonstrating how to
apply every supported meta-heuristics to the classic
[traveling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem).
