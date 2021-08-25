---
abtract: Accurate segmentation of volumetric scans like MRI and CT scans is highly
  demanded for surgery planning in clinical practice, quantitative analysis, and identification
  of disease. However, accurate segmentation is challenging because of the irregular
  shape of given organ and large variation in appearances across the slices. In such
  problems, 3D features are desired in nature which can be extracted using 3D convolutional
  neural network (CNN). However, 3D CNN is compute and memory intensive to implement
  due to large number of parameters and can easily over fit, especially in medical
  imaging where training data is limited. In order to address these problems, we propose
  a distillation-based depth shift module (Distill DSM). It is designed to enable
  2D convolutions to make use of information from neighbouring frames more efficiently.
  Specifically, in each layer of the network, Distill DSM learns to extract information
  from a part of the channels and shares it with neighbouring slices, thus facilitating
  information exchange among neighbouring slices. This approach can be incorporated
  with any 2D CNN model to enable it to use information across the slices with introducing
  very few extra learn-able parameters. We have evaluated our model on BRATS 2020,
  heart, hippocampus, pancreas and prostate dataset. Our model achieves better performance
  than 3D CNN for heart and prostate datasets and comparable performance on BRATS
  2020, pancreas and hippocampus dataset with simply 28\% of parameters compared to
  3D CNN model.
booktitle: Medical Imaging with Deep Learning
title: 'Distill DSM: Computationally efficient method for segmentation of medical
  imaging volumes'
openreview: _n48l6YKc6d
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: maheshwari21a
month: 0
tex_title: 'Distill {DSM}: Computationally efficient method for segmentation of medical
  imaging volumes'
firstpage: 473
lastpage: 483
page: 473-483
order: 473
cycles: false
bibtex_author: Maheshwari, Harsh and Goel, Vidit and Sethuraman, Ramanathan and Sheet,
  Debdoot
author:
- given: Harsh
  family: Maheshwari
- given: Vidit
  family: Goel
- given: Ramanathan
  family: Sethuraman
- given: Debdoot
  family: Sheet
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
pdf: https://proceedings.mlr.press/v143/maheshwari21a/maheshwari21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
