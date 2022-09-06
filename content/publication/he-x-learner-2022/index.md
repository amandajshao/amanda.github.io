---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'X-Learner: Learning Cross Sources and Tasks for Universal Visual Representation'
subtitle: ''
summary: ''
authors:
- Yinan He
- Gengshi Huang
- Siyu Chen
- Jianing Teng
- Wang Kun
- Zhenfei Yin
- Lu Sheng
- Ziwei Liu
- Yu Qiao
- Jing Shao
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
-
-
-
-
-
- "Corresponding author"
tags: []
categories: []
date: '2022-07-16'
lastmod: 2022-08-26T23:26:32+08:00
featured: true
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
projects: ["multi-task-learning"]
publishDate: '2022-08-26T15:26:32.526953Z'
publication_types:
- '1'
abstract: 'In computer vision, pre-training models based on largescale supervised learning have been proven effective over the past few years. However, existing works mostly focus on learning from individual task with single data source (e.g., ImageNet for classification or COCO for detection). This restricted form limits their generalizability and usability due to the lack of vast semantic information from various tasks and data sources. Here, we demonstrate that jointly learning from heterogeneous tasks and multiple data sources contributes to universal visual representation, leading to better transferring results of various downstream tasks. Thus, learning how to bridge the gaps among different tasks and data sources is the key, but it still remains an open question. In this work, we propose a representation learning framework called X-Learner, which learns the universal feature of multiple vision tasks supervised by various sources, with expansion and squeeze stage: 1) Expansion Stage: X-Learner learns the task-specific feature to alleviate task interference and enrich the representation by reconciliation layer. 2) Squeeze Stage: X-Learner condenses the model to a reasonable size and learns the universal and generalizable representation for various tasks transferring. Extensive experiments demonstrate that X-Learner achieves strong performance on different tasks without extra annotations, modalities and computational costs compared to existing representation learning methods. Notably, a single X-Learner model shows remarkable gains of 3.0%, 3.3% and 1.8% over current pretrained models on 12 downstream datasets for classification, object detection and semantic segmentation.'
publication: 'European Conference on Computer Vision (**ECCV**), 2022'

url_pdf: "http://arxiv.org/abs/2203.08764"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

---
