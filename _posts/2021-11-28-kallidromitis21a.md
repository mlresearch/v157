---
title: Contrastive Neural Processes for Self-Supervised Learning
section: Contributed Papers
crossref: acml21
abstract: Recent contrastive methods show significant improvement in self-supervised
  learning in several domains. In particular, contrastive methods are most effective
  where data augmentation can be easily constructed e.g. in computer vision. However,
  they are less successful in domains without established data transformations such
  as time series data. In this paper, we propose a novel self-supervised learning
  framework that combines contrastive learning with neural processes. It relies on
  recent advances in neural processes to perform time series forecasting. This allows
  to generate augmented versions of data by employing a set of various sampling functions
  and, hence, avoid manually designed augmentations. We extend conventional neural
  processes and propose a new contrastive loss to learn times series representations
  in a self-supervised setup. Therefore, unlike previous self-supervised methods,
  our augmentation pipeline is task-agnostic, enabling our method to perform well
  across various applications. In particular, a ResNet with a linear classifier trained
  using our approach is able to outperform state-of-the-art techniques across industrial,
  medical and audio datasets improving accuracy over 10% in ECG periodic data. We
  further demonstrate that our self-supervised representations are more efficient
  in the latent space, improving multiple clustering indexes and that fine-tuning
  our method on 10% of labels achieves results competitive to fully-supervised learning.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kallidromitis21a
month: 0
tex_title: Contrastive Neural Processes for Self-Supervised Learning
firstpage: 594
lastpage: 609
page: 594-609
order: 594
cycles: false
bibtex_author: Kallidromitis, Konstantinos and Gudovskiy, Denis and Kazuki, Kozuka
  and Iku, Ohama and Rigazio, Luca
author:
- given: Konstantinos
  family: Kallidromitis
- given: Denis
  family: Gudovskiy
- given: Kozuka
  family: Kazuki
- given: Ohama
  family: Iku
- given: Luca
  family: Rigazio
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
pdf: https://proceedings.mlr.press/v157/kallidromitis21a/kallidromitis21a.pdf
extras:
- label: Supplementary ZIP
  link: https://proceedings.mlr.press/v157/kallidromitis21a/kallidromitis21a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
