---
title: "Accelerating the Lagrangian particle tracking in hydrology to continental-scale"
collection: publications
permalink: /publication/2023-05-10-paper-title-number-4
excerpt: 'This paper is about the GPU acceleration of particle tracking.'
date: 2023-05-10
venue: 'Journal of Advances in Modeling Earth Systems'
paperurl: 'https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2022MS003507'
#citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Unprecedented climate change and anthropogenic activities have induced increasing ecohydrological problems, motivating the development of large-scale hydrologic modeling for solutions. Water age/quality is as important as water quantity for understanding the terrestrial water cycle. However, scientific progress in tracking water parcels at large-scale with high spatiotemporal resolutions is far behind that in simulating water balance/quantity owing to the lack of powerful modeling tools. EcoSLIM is a particle tracking model working with ParFlow-CLM that couples integrated surface-subsurface hydrology with land surface processes. Here, we demonstrate a parallel framework on distributed, multi-Graphics Processing Unit platforms with Compute Unified Device Architecture-Aware Message Passing Interface for accelerating EcoSLIM to continental-scale. In tests from catchment-, to regional-, and then to continental-scale using 25-million to 1.6-billion particles, EcoSLIM shows significant speedup and excellent parallel performance. The parallel framework is portable to atmospheric and oceanic particle tracking models, where the parallelization is inadequate, and a standard parallel framework is also absent. The parallelized EcoSLIM is a promising tool to accelerate our understanding of the terrestrial water cycle and the upscaling of subsurface hydrology to Earth System Models.
