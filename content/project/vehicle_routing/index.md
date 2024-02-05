---
title: Fast Same-Day Delivery Optimization
summary: A collaboration between Swiss Post / Notime and ETH Zurich.
tags:
  - Optimization
date: '2024-02-05T00:00:00Z'
# Optional external URL for project (replaces project detail page).
# external_link: ''

# links:
#   - icon: github
#     icon_pack: fab
#     name: Code
#     url: https://github.com/test
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''
---
### Project Objectives:
The collaboration between ETH Zurich and Swiss Post / Notime aims to optimize same-day shipment delivery in Zurich, Bern 
and other Swiss cities. The primary objectives include efficiently managing deliveries within specified time windows, 
considering driver shift schedules, vehicle capacity constraints, and minimizing both overtime costs and total driving 
distance. Notably, the algorithm is designed to be exceptionally fast, ensuring real-time optimization for dynamic delivery 
scenarios.
<center>{{< figure src="driver_assignment.png" caption="As a sub-routine the individual drivers are assigned optimally to the tours." numbered="true" >}}</center>

### Key Features:
- Optimization Algorithm:
The project utilizes a sophisticated optimization algorithm written in Scala 3. Employing local-search meta-heuristics and 
leveraging state-of-the-art traveling salesman subroutines, the algorithm intelligently plans and optimizes delivery routes, 
with a strong emphasis on speed for real-time planning.
- Hub-Centric Approach:
Shipments originate from a central hub, and the algorithm efficiently manages distribution to destinations within specified 
time windows. It takes into account vehicle capacities and driver shift constraints, optimizing routes in real-time to meet 
stringent delivery timelines.
- Asymmetric Travel Time Handling:
The algorithm accommodates asymmetric travel times, considering the challenges posed by one-way roads and varying terrains. 
This feature is particularly crucial for efficient bicycle-based deliveries.
- Cost Minimization:
The optimization algorithm prioritizes the minimization of overall delivery costs, with a particular emphasis on mitigating 
driver overtime expenses. This approach aims to ensure economic and sustainable delivery operations without compromising on speed.
- Driving Distance Optimization:
Alongside time-related constraints, the algorithm focuses on minimizing the total driving distance. This dual optimization 
strategy, executed at remarkable speed, promotes environmentally friendly and resource-efficient delivery routes.
<center>{{< figure src="segment_swap.png" caption="For a swap a segment of shipments are moved from the provider's to the receiver's tour." numbered="true">}}</center>

### Technological Stack:
The project leverages a robust technological stack to implement and deploy the optimization algorithm:

- Scala 3: The core programming language for developing the optimization algorithm.
- Docker: Used for containerization, providing a consistent and isolated environment for seamless deployment across different systems.
- HTTP Server: Facilitates communication and interaction with the optimization algorithm, allowing for efficient integration 
into various systems and platforms.

### Project Leadership:
I led this collaborative effort, taking charge of project management, strategy, and actively participating in the development process.
As a key contributor, my role also involves the design, development, and implementation of the optimization algorithm. 
Leveraging Scala 3, Docker, and an HTTP server,
