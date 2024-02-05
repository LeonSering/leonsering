---
title: Drawing Road Networks with Focus Regions
authors:
- Jan-Henrik Haunert
- Leon Sering
date: '2011-01-01'
publishDate: '2024-02-04T16:35:34.893834Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Visualization and Computer Graphics*'
doi: 10.1109/TVCG.2011.191
abstract: Mobile users of maps typically need detailed information about their surroundings
  plus some context information about remote places. In order to avoid that the map
  partly gets too dense, cartographers have designed mapping functions that enlarge
  a user-defined focus region - such functions are sometimes called fish-eye projections.
  The extra map space occupied by the enlarged focus region is compensated by distorting
  other parts of the map. We argue that, in a map showing a network of roads relevant
  to the user, distortion should preferably take place in those areas where the network
  is sparse. Therefore, we do not apply a predefined mapping function. Instead, we
  consider the road network as a graph whose edges are the road segments. We compute
  a new spatial mapping with a graph-based optimization approach, minimizing the square
  sum of distortions at edges. Our optimization method is based on a convex quadratic
  program (CQP); CQPs can be solved in polynomial time. Important requirements on
  the output map are expressed as linear inequalities. In particular, we show how
  to forbid edge crossings. We have implemented our method in a prototype tool. For
  instances of different sizes, our method generated output maps that were far less
  distorted than those generated with a predefined fish-eye projection. Future work
  is needed to automate the selection of roads relevant to the user. Furthermore,
  we aim at fast heuristics for application in real-time systems.
---
 A preliminary version was presented at IEEE Information Visualization Conference (INFOVIS'11).
