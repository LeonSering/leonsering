---
title: Fair and Fast k-Center Clustering
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
    url: https://github.com/LeonSering/fair_and_fast_k_center_clustering
  - name: Publication
    url: /publication/angelidakis-2022-fair
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''
---
### Project Objectives:
This project revolves around the development of a highly efficient k-center algorithm, which was accepted at the International Conference on Machine Learning (ICML). The algorithm addresses two key issues faced by many clustering methods when used for data summarization:

1. Unfair representation of “demographic groups”.
2. Distorted summarizations, where data points in the summary represent subsets of the original data of vastly different sizes.

Our algorithm effectively addresses both issues simultaneously by presenting a clustering procedure that works for a canonical combined model. It is fast, both in theory and practice, with a linear-running time in the number of points, exhibits a worst-case constant-factor guarantee, and gives promising computational results showing that there can be significant benefits in addressing both issues together instead of sequentially.

This project represents a significant step forward in the field of data summarization and clustering, offering a more fair and accurate representation of data. It has potential applications in a wide range of fields, from machine learning and data science to bioinformatics and network analysis.

For more details, please refer to our [ICML paper]({{< relref "/publication/angelidakis-2022-fair" >}}).
<center>{{< figure src="plots.png" caption="Comparison to the previous best algorithm by Jones, Nguyen, and Nguyen from 2020 with and without privacy constraint." numbered="true">}}</center>

### Technological Stack:
The algorithm is developed in Rust, utilizing very fast parallel computing. It incorporates matching algorithms, flow algorithms, and other graph algorithms. Additionally, it provides Python bindings for ease of integration with Python-based projects.
<center>{{< figure src="flow_network.png" caption="The algorithm utilizes fast maximum flow computation to open representative centers." numbered="true">}}</center>

