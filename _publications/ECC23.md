---
title: "An online path planner based on POMDP for UAVs"
collection: publications
permalink: /publications/ECC23
venue: "2023 European Control Conference (ECC)"
---

Links: [ieee]](https://ieeexplore.ieee.org/abstract/document/9655037)

## Abstract
Path planning for Unmanned Aerial Vehicles (UAVs) is a challenging and important problem that received significant attention in recent years. 
In this paper we focus on Partially Observable Markov Decision Processes (POMDP), a powerful and popular model for planning and control that has several applications on UAVs (e.g search \& rescue, surveillance, or automatic warehouse). 
In particular, we propose a methodology to plan trajectories that allow UAVs to reach a target while avoiding no-fly zones, optimizing, e.g, fuel consumption, flight time, or constraining the approaching angle.
The fixed-wing aircraft dynamic is considered in the problem formulation and an uncertainty model error is added to take into account the approximations.
The sensing system providing observations of the aircraft state consists of a GPS sensor, an Inertial Navigation System (INS), and other onboard sensors.
Considering the complexity of the domain and following the recent literature, we propose an online solution approach based on Monte Carlo Tree Search (MCTS). The online nature of the approach mitigates the complexity typically associated with POMDP models by avoiding the computation of the whole policy.
This approach has been validated and tested in simulation on different scenarios and with different cost functions.

### Bibtex

    @inproceedings{trotti2021modified,
        title={A Modified Recursive Newton-Euler Algorithm Embedding a Collision Avoidance Module},
        author={Trotti, Francesco and Ghignoni, Eros and Muradore, Riccardo},
        booktitle={2021 European Control Conference (ECC)},
        pages={1150--1155},
        year={2021},
        organization={IEEE}
    }