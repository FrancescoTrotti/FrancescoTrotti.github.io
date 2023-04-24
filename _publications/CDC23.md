---
title: "A POMDP-based Approach for Autopilot Control of Aircrafts"
collection: publications
permalink: /publications/CDC23
venue: "62nd IEEE International Conference on Decision and Control"
---

Links: 

## Abstract
The autopilot problem for aircraft is an important and challenging issue that has received significant attention in recent years. 
In this paper, we propose an autopilot controller to plan the trajectory of an aircraft by providing optimal commands to reach the target while avoiding no-fly zones and optimizing travel distance. Our approach uses a solver for Partially Observable Markov Decision Processes (POMDP) as the high-level controller (outer loop) and an inverse dynamics controller as the low-level controller (inner loop) to provide the correct commands. The POMDP provides the reference values to the low-level controller for commanding the actuators. By using a linearized dynamic model obtained from dynamics inversion, the POMDP can efficiently compute optimal reference values. We successfully validated and tested this approach in a simulated scenario where the aircraft must reach a target position while avoiding no-fly zones.

