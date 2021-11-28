---
title: Time-Constrained Multi-Agent Path Finding in Non-Lattice Graphs with Deep Reinforcement
  Learning
section: Contributed Papers
crossref: acml21
abstract: Multi-Agent Path Finding (MAPF) is a routing problem in which multiple agents
  need to each find a lowest-cost collection of routes in a graph that avoids collisions
  between agents. This problem occurs frequently in the domain of logistics, for example
  in the routing of trains in shunting yards, airplanes at airports, and picking robots
  in automated warehouses. A solution is presented for the MAPF problem in which agents
  operate on an arbitrary directed graph, rather than the commonly assumed grid world,
  which extends support to use cases where the environment cannot be easily modeled
  in a grid shape. Furthermore, constraints are introduced on the start and end times
  of the routing tasks, which is vital in MAPF problems that are part of larger logistics
  systems. A Reinforcement Learning-based (RL) approach is proposed to learn a local
  routing policy for an agent in a manner that relieves the need for manually designing
  heuristics. It relies on a Graph Convolutional Network to handle arbitrary graphs.
  Both single-agent and multi-agent RL approaches are presented, showing how a multi-agent
  setup can reduce training time by exploiting the similarities in agent properties
  and local graph topologies.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: knippenberg21a
month: 0
tex_title: Time-Constrained Multi-Agent Path Finding in Non-Lattice Graphs with Deep
  Reinforcement Learning
firstpage: 1317
lastpage: 1332
page: 1317-1332
order: 1317
cycles: false
bibtex_author: van Knippenberg, Marijn and Holenderski, Mike and Menkovski, Vlado
author:
- given: Marijn
  family: Knippenberg
  prefix: van
- given: Mike
  family: Holenderski
- given: Vlado
  family: Menkovski
date: 2021-11-28
address:
container-title: Proceedings of The 13th Asian Conference on Machine Learning
volume: '157'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 11
  - 28
pdf: https://proceedings.mlr.press/v157/knippenberg21a/knippenberg21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
