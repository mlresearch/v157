---
title: Max-Utility Based Arm Selection Strategy For Sequential Query Recommendations
section: Contributed Papers
crossref: acml21
abstract: We consider the query recommendation problem in closed loop interactive
  learning settings like online information gathering and exploratory analytics. The
  problem can be naturally modelled using the Multi-Armed Bandits (MAB) framework
  with countably many arms. The standard MAB algorithms for countably many arms begin
  with selecting a random set of candidate arms and then applying standard MAB algorithms,
  e.g., UCB, on this candidate set downstream. We show that such a selection strategy
  often results in higher cumulative regret and to this end, we propose a selection
  strategy based on the maximum utility of the arms. We show that in tasks like online
  information gathering, where sequential query recommendations are employed, the
  sequences of queries are correlated and the number of potentially optimal queries
  can be reduced to a manageable size by selecting queries with maximum utility with
  respect to the currently executing query. Our experimental results using a recent
  real online literature discovery service log file demonstrate that the proposed
  arm selection strategy improves the cumulative regret substantially with respect
  to the state-of-the-art baseline algorithms. Our data model and source code are
  available at  \url{https://anonymous.4open.science/r/0e5ad6b7-ac02-4577-9212-c9d505d3dbdb/}
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: puthiya-parambath21a
month: 0
tex_title: Max-Utility Based Arm Selection Strategy For Sequential Query Recommendations
firstpage: 564
lastpage: 579
page: 564-579
order: 564
cycles: false
bibtex_author: Puthiya Parambath, Shameem and Anagnostopoulos, Christos and Murray-Smith,
  Roderick and MacAvaney, Sean and and Zervas, Evangelos
author:
- given: Shameem
  family: Puthiya Parambath
- given: Christos
  family: Anagnostopoulos
- given: Roderick
  family: Murray-Smith
- given: Sean
  family: MacAvaney
- given: Evangelos
  family: Zervas
  prefix: and
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
pdf: https://proceedings.mlr.press/v157/puthiya-parambath21a/puthiya-parambath21a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v157/puthiya-parambath21a/puthiya-parambath21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
