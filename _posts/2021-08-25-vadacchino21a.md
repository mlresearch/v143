---
abstract: 'Segmentation of enhancing tumours or lesions from MRI is important for
  detecting new disease activity in many clinical contexts. However, accurate segmentation
  requires the inclusion of medical images (e.g., T1 post-contrast MRI) acquired after
  injecting patients with a contrast agent (e.g., Gadolinium), a process no longer
  thought to be safe. Although a number of modality-agnostic segmentation networks
  have been developed over the past few years, they have been met with limited success
  in the context of enhancing pathology segmentation. In this work, we present HAD-Net,
  a novel offline adversarial knowledge distillation (KD) technique, whereby a pre-trained
  teacher segmentation network, with access to all MRI sequences, teaches a student
  network, via hierarchical adversarial training, to better overcome the large domain
  shift presented when crucial images are absent during inference. In particular,
  we apply HAD-Net to the challenging task of enhancing tumour segmentation when access
  to post-contrast imaging is not available. The proposed network is trained and tested
  on the BraTS 2019 brain tumour segmentation challenge dataset, where it achieves
  performance improvements in the ranges of 16% - 26% over (a) recent modality-agnostic
  segmentation methods (U-HeMIS, U-HVED), (b) KD-Net adapted to this problem, (c)
  the pre-trained student network and (d) a non-hierarchical version of the network
  (AD-Net), in terms of Dice scores for enhancing tumour (ET). The network also shows
  improvements in tumour core (TC) Dice scores. Finally, the network outperforms both
  the baseline student network and AD-Net in terms of uncertainty quantification for
  enhancing tumour segmentation based on the BraTS 2019 uncertainty challenge metrics.
  Our code is publicly available at: https://github.com/SaverioVad/HAD_Net'
booktitle: Medical Imaging with Deep Learning
title: 'HAD-Net: A Hierarchical Adversarial Knowledge Distillation Network for Improved
  Enhanced Tumour Segmentation Without Post-Contrast Images'
openreview: 48UgSFrNR2
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vadacchino21a
month: 0
tex_title: 'HAD-Net: A Hierarchical Adversarial Knowledge Distillation Network for
  Improved Enhanced Tumour Segmentation Without Post-Contrast Images'
firstpage: 787
lastpage: 801
page: 787-801
order: 787
cycles: false
bibtex_author: Vadacchino, Saverio and Mehta, Raghav and Sepahvand, Nazanin Mohammadi
  and Nichyporuk, Brennan and Clark, James J. and Arbel, Tal
author:
- given: Saverio
  family: Vadacchino
- given: Raghav
  family: Mehta
- given: Nazanin Mohammadi
  family: Sepahvand
- given: Brennan
  family: Nichyporuk
- given: James J.
  family: Clark
- given: Tal
  family: Arbel
date: 2021-08-25
address:
container-title: Proceedings of the Fourth Conference on Medical Imaging with Deep
  Learning
volume: '143'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 8
  - 25
pdf: https://proceedings.mlr.press/v143/vadacchino21a/vadacchino21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
