---
title: Focus Region Tool
summary: A tool to enlarge a focus region in a road map while minimizing the distortion by convex quadratic programming.
tags:
  - Major
  - Optimization
date: '2011-01-01T00:00:00Z'
# Optional external URL for project (replaces project detail page).
# external_link: ''

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/LeonSering/focus_region
  - name: Publication
    url: publication/haunert-2011-roadmap
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''
---
I developed this tool during the research project on "focus regions" at the university of Würzburg in collaboration
with Jan-Henrik Haunert. This leads to my [first publication](/publication/haunert-2011-roadmap).

### Project Objective:
The tool allows the user to choose a focus region within a larger area on a road map, together with a zoom factor.
By solving a convex quadratic program a new visualization of the road map is created, where all elements in the
focus region are scaled by the zoom factor, all elements outside the area stay untouched and the elements within the
area but outside the focus region are moved such that the distortions are minimized.

<center>{{< figure src="focus_region.png" caption="Left: The original road map of Boston. Right: The focus region is enlarged by a factor of 3." numbered="true" >}}</center>

The result is a new map, where the focus region is strongly enlarged, but still the map looks topologically very
similar to the original map.

A typical use case is the visualization of a long route from a dense city to another dense city on a GPS unit.
You can enlarge the area close to the origin and destination, where typically a lot of small roads are important
for the driver. The route on the highway between the cities is usually easier to navigate, so it could be shrunk.

The result is a visualization of the whole route within a road map that still looks quite similar to the original one,
but the two focus regions are enlarged such that each turn is clearly visible.

<center>{{< figure src="focus_region_tool.png" caption="The tool support multiple focus regions and several optimization options." numbered="true" >}}</center>

### Technological Stack:
The software is written in JAVA and uses CPLEX for solving a convex quadratic program.
