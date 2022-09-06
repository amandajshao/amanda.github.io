---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Slicing Convolutional Neural Network for Crowd Video Understanding
subtitle: ''
summary: ''
authors:
- Jing Shao
- Chen Change Loy
- Kai Kang
- Xiaogang Wang
tags:
- Dynamics
- Feature extraction
- Ice
- Semantics
- Three-dimensional displays
- Two dimensional displays
- Visualization
categories: []
date: '2016-06-01'
lastmod: 2022-08-26T23:26:31+08:00
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
projects: ["crowd-behavior-understanding"]
publishDate: '2022-08-26T15:26:31.758117Z'
publication_types:
- '1'
abstract: 'Learning and capturing both appearance and dynamic representations are
  pivotal for crowd video understanding. Convolutional Neural Networks (CNNs) have
  shown its remarkable potential in learning appearance representations from images.
  However, the learning of dynamic representation, and how it can be effectively combined
  with appearance features for video analysis, remains an open problem. In this study,
  we propose a novel spatio-temporal CNN, named Slicing CNN (S-CNN), based on the
  decomposition of 3D feature maps into 2D spatio-and 2D temporal-slices representations.
  The decomposition brings unique advantages: (1) the model is capable of capturing
  dynamics of different semantic units such as groups and objects, (2) it learns separated
  appearance and dynamic representations while keeping proper interactions between
  them, and (3) it exploits the selectiveness of spatial filters to discard irrelevant
  background clutter for crowd understanding. We demonstrate the effectiveness of
  the proposed S-CNN model on the WWW crowd video dataset for attribute recognition
  and observe significant performance improvements to the state-of-the-art methods
  (62.55% from 51.84% [21]).'
publication: 'IEEE Conference on Computer Vision and Pattern Recognition (**CVPR**), <span style="color:red">**Spotlight**</span>, 2016'
doi: 10.1109/CVPR.2016.606
---
