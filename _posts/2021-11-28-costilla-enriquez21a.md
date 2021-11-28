---
title: Exposing Cyber-Physical System Weaknesses by Implicitly Learning their Underlying
  Models
section: Contributed Papers
crossref: acml21
abstract: Cyber-Physical Systems (CPS) plays a critical role in today’s social life,
  especially with occasional pandemic events. With more reliance on the cyber operation
  of infrastructures, it is important to understand attacking mechanisms in CPS for
  potential solutions and defenses, where False Data Injection Attack (FDIA) is an
  important class. FDIA methods in the literature require the mathematical CPS model
  and state variable values to create an efficient attack vector, unrealistic for
  many attackers in the real world. Also, they do not have performance guarantee.
  This paper shows that it is possible to deploy a FDIA without having the CPS model
  and state variables information. Additionally, we prove a theoretic bound for the
  proposed method. Specifically, we design a scheme that learns an implicit CPS model
  to create tampered sensor measurements to deploy an attack based only on historical
  data. The proposed framework utilizes a Wasserstein generative adversarial network
  with two regularization terms to create such tampered measurements also known as
  adversarial examples. To build an attack with confidence, we present a proof based
  on convergence in distribution and Lipschitz norm to show that our method captures
  the real observed measurement distribution. This means that our model learns the
  complex underlying processes from the CPSs. We demonstrate the robustness and universality
  of our proposed framework based on two diversified adversarial examples with different
  systems, domains, and datasets.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: costilla-enriquez21a
month: 0
tex_title: Exposing Cyber-Physical System Weaknesses by Implicitly Learning their
  Underlying Models
firstpage: 1333
lastpage: 1348
page: 1333-1348
order: 1333
cycles: false
bibtex_author: Costilla-Enriquez, Napoleon and Weng, Yang
author:
- given: Napoleon
  family: Costilla-Enriquez
- given: Yang
  family: Weng
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
pdf: https://proceedings.mlr.press/v157/costilla-enriquez21a/costilla-enriquez21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
