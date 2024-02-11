---
title: Nash Flow Computation
summary: A linear-time k-center algorithm with fairness conditions and worst-case guarantees that is very fast in practice.
  Written in Rust with Python bindings.
tags:
  - Major
  - Optimization
date: '2022-01-28T00:00:00Z'
# Optional external URL for project (replaces project detail page).
# external_link: ''

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/LeonSering/NashFlowComputation
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''
---
### Project Objective
The Nash Flow Computation Tool (NFC) is a Python-based project that uses the SCIP mixed integer program solver
to compute (spillback) thin flows, and consequently, Nash flows over time with or without spillback, as it is
descriped in [this paper](/publication/sering-2019-spillback) and [my thesis](/publication/sering-2020-diss).

<center>{{< figure src="nfc_input.png" caption="The network can be created by drag and drop." numbered="true">}}</center>

### Features
NFC is embedded in a user-friendly graphical interface, enabling quick and easy creation of networks.
It allows the analysis of earliest arrival time functions and inflow functions in a dynamic equilibrium, which can be
computed with a single click for further research.
The flow models used are based on specific references for the basic case without spillback and for the case with spillback.
The algorithms to compute thin flows are based on established research.

<center>{{< figure src="nfc_output.png" caption="The application provides all relevant information about the computed Nash flow over time." numbered="true">}}</center>

### Tools and Libraries
The project makes use of the following tools and libraries:
Python 3.7, PyQt5, matplotlib, numpy, networkx, SCIP.

### Development
NFC was initially developed as part of the bachelor thesis of Max Zimmer and was later enhanced within the TU Berlin/ECMath
project titled “Dynamic Models and Algorithms for Equilibria in Traffic Networks”.

### My Role
As a supervisor, I guided the developer throughout the project, ensuring the successful implementation of the tool and its features.
