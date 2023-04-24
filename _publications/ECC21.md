---
title: "A Modified Recursive Newton-Euler Algorithm Embedding a Collision Avoidance Module"
collection: publications
permalink: /publications/ECC21
venue: "2021 European Control Conference (ECC)"
---

Links: 
[ieee]](https://ieeexplore.ieee.org/abstract/document/9655037)

## Abstract
Planning collision-free trajectories for robotic manipulators is a quite old problem that has recently re-gained importance thanks to collaborative robotics. In scenarios where a robot is moving close to an operator, it is of paramount importance to detect obstacles (e.g. human' arms) that must be avoided. When the environment is dynamic this problem is still challenging. In this paper we integrate a recent collision avoidance algorithm based on the efficient computation of distances between capsules and the environment into the well-known recursive Newton-Euler algorithm for computing the inverse dynamics of serial-link manipulators. This approach allows to compute repulsive torques at the joint level that guarantee collision-free motion at run-time. The proposed approach has been validated on a simulated environment using a six degrees of freedom UR5 robot.

### Bibtex

    @inproceedings{trotti2021modified,
        title={A Modified Recursive Newton-Euler Algorithm Embedding a Collision Avoidance Module},
        author={Trotti, Francesco and Ghignoni, Eros and Muradore, Riccardo},
        booktitle={2021 European Control Conference (ECC)},
        pages={1150--1155},
        year={2021},
        organization={IEEE}
    }