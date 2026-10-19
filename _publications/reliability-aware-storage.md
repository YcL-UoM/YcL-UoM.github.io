---
title: "Reliability-Aware Storage Target Design via Decomposed Real-Time Feasibility Cuts"
collection: publications
category: working
permalink: /publication/reliability-aware-storage/
status: "Working paper"
excerpt: ""
share: false
---

## Abstract

The increasing penetration of renewable generation, coupled with rapidly growing electricity demand from data centers, intensifies net-load variability and uncertainty. Energy storage provides critical flexibility, but designing state-of-charge (SoC) targets that coordinate day-ahead dispatch with real-time operations remains an open challenge. This paper proposes a two-stage reliability-aware framework for storage target design. The first stage determines day-ahead dispatch schedules and SoC targets, while the second stage evaluates real-time reliability by decomposing the problem into scenario-window subproblems. Using sensitivities from violated subproblems, we construct dual-based reliability cuts that iteratively refine SoC targets as dispatch schedules are reoptimized under fixed slow-generator commitments. For a reduced convex formulation, we derive contextual finite-sample reliability guarantees and compare sufficient sample budgets with an unconditional-sampling baseline for certifying the same conditional risk. Numerical studies demonstrate the computational advantages of system-aggregate and PTDF-zonal targets and characterize the impact of spatial granularity on convergence. Sequential simulations show that the proposed SoC targets can completely eliminate load shedding under critical conditions with only a 0.70% increase in day-ahead operating costs.

## Authors

**Yichen Li**, Ruiwei Jiang, and Alexandre Moreira.
