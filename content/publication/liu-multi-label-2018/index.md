---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multi-Label Image Classification via Knowledge Distillation from Weakly-Supervised
  Detection
subtitle: ''
summary: ''
authors:
- Yongcheng Liu
- Lu Sheng
- Jing Shao
- Junjie Yan
- Shiming Xiang
- Chunhong Pan
author_notes:
-
- 
- "Corresponding author"
tags:
- knowledge distillation
- multi-label image classification
- weakly-supervised detection
categories: []
date: '2018-10-15'
lastmod: 2022-08-26T23:26:28+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["image-classification"]
publishDate: '2022-08-26T15:26:28.689518Z'
publication_types:
- '1'
abstract: Multi-label image classification is a fundamental but challenging task towards
  general visual understanding. Existing methods found the region-level cues (e.g.,
  features from RoIs) can facilitate multi-label classification. Nevertheless, such
  methods usually require laborious object-level annotations (i.e., object labels
  and bounding boxes) for effective learning of the object-level visual features.
  In this paper, we propose a novel and efficient deep framework to boost multi-label
  classification by distilling knowledge from weakly-supervised detection task without
  bounding box annotations. Specifically, given the image-level annotations, (1) we
  first develop a weakly-supervised detection (WSD) model, and then (2) construct
  an end-to-end multi-label image classification framework augmented by a knowledge
  distillation module that guides the classification model by the WSD model according
  to the class-level predictions for the whole image and the object-level visual features
  for object RoIs. The WSD model is the teacher model and the classification model
  is the student model. After this cross-task knowledge distillation, the performance
  of the classification model is significantly improved and the efficiency is maintained
  since the WSD model can be safely discarded in the test phase. Extensive experiments
  on two large-scale datasets (MS-COCO and NUS-WIDE) show that our framework achieves
  superior performances over the state-of-the-art methods on both performance and
  efficiency.
publication: 'ACM International Conference on Multimedia (**MM**), 2018'
doi: 10.1145/3240508.3240567

url_pdf: "https://arxiv.org/abs/1809.05884"
url_code: "https://github.com/Yochengliu/MLIC-KD-WSD"
url_dataset: 
url_poster:
url_project: "https://yochengliu.github.io/MLIC-KD-WSD/"
url_slides:
url_source:
url_video:
---
