---
title: Rolling Stock Scheduling Optimization
summary: A collaboration between Swiss Federal Railways (SBB) and ETH Zurich.
tags:
  - Major
  - Optimization
date: '2024-02-05T00:00:00Z'
# Optional external URL for project (replaces project detail page).
# external_link: ''

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/LeonSering/eth_sbb_rolling_stock_scheduling
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''
---
### Project Objectives:
In anticipation of the mobility landscape in the year 2050, Swiss Federal Railways (SBB) faces a crucial challenge -- ensuring a 
seamlessly efficient rail service. The primary focus is on optimizing rolling stock schedules within the evolving context of 
futuristic mobility scenarios. The key objectives of this project are to minimize rolling stock units and the overall travel 
distance, while adhering to strict maintenance regulations and meeting the dynamic passenger demand.
<center>{{< figure src="schedule.png" caption="Optimized rolling stock schedule." numbered="true" >}}</center>

### Optimization Approach:
Integrating cutting-edge methodologies, our optimization approach seamlessly combines local-search-metaheuristics 
and classic minimum-cost flow algorithms. The strategy systematically refines rolling stock schedules through small, 
local modifications, such as exchanging adjusting train compositions, or exchanging a 
sequence of service trips to another rolling stock vehicle. Simultaneously, 
the optimality of classic minimum-cost flow algorithms ensures minimal overall costs.
<center>{{< figure src="swap.png" caption="A swap by exchanging a sequence of service trips." numbered="true">}}</center>

### Technological Stack:
The project leverages a robust technological stack to implement and deploy the optimization algorithm:
- Rust: The core programming language, providing high performance, reliability, and enabling parallelism for efficient utilization of computational resources.
- Docker: Used for containerization, ensuring a consistent and isolated environment for seamless deployment across different systems.
- HTTP Server: Facilitating communication and interaction with the optimization algorithm, ensuring strict and reliable interfaces for efficient integration into various systems and platforms.

### Project Leadership
I take charge as the primary project lead, leading the coding efforts in Rust and implementing state-of-the-art algorithms. 
Additionally, I supervise student projects, contributing to this project success.
