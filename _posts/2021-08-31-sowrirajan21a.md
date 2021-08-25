---
abstract: Contrastive learning is a form of self-supervision that can leverage unlabeled
  data to produce pretrained models. While contrastive learning has demonstrated promising
  results on natural image classification tasks, its application to medical imaging
  tasks like chest X-ray interpretation has been limited. In this work, we propose
  MoCo-CXR, which is an adaptation of the contrastive learning method Momentum Contrast
  (MoCo), to produce models with better representations and initializations for the
  detection of pathologies in chest X-rays. In detecting pleural effusion, we find
  that linear models trained on MoCo-CXR-pretrained representations outperform those
  without MoCo-CXR-pretrained representations, indicating that MoCo-CXR-pretrained
  representations are of higher-quality. End-to-end fine-tuning experiments reveal
  that a model initialized via MoCo-CXR-pretraining outperforms its non-MoCo-CXR-pretrained
  counterpart. We find that MoCo-CXR-pretraining provides the most benefit with limited
  labeled training data. Finally, we demonstrate similar results on a target Tuberculosis
  dataset unseen during pretraining, indicating that MoCo-CXR-pretraining endows models
  with representations and transferability that can be applied across chest X-ray
  datasets and tasks.
booktitle: Medical Imaging with Deep Learning
title: MoCo Pretraining Improves Representation and Transferability of Chest X-ray
  Models
openreview: LO7Su0-dPJl
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sowrirajan21a
month: 0
tex_title: MoCo Pretraining Improves Representation and Transferability of Chest X-ray
  Models
firstpage: 728
lastpage: 744
page: 728-744
order: 728
cycles: false
bibtex_author: Sowrirajan, Hari and Yang, Jingbo and Ng, Andrew Y. and Rajpurkar,
  Pranav
author:
- given: Hari
  family: Sowrirajan
- given: Jingbo
  family: Yang
- given: Andrew Y.
  family: Ng
- given: Pranav
  family: Rajpurkar
date: 2021-08-31
address:
container-title: Proceedings of the Fourth Conference on Medical Imaging with Deep
  Learning
volume: '143'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 8
  - 31
pdf: https://proceedings.mlr.press/v143/sowrirajan21a/sowrirajan21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
