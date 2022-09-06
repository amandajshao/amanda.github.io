---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Zoom-Net: Mining Deep Feature Interactions for Visual Relationship Recognition'
subtitle: ''
summary: ''
authors:
- Guojun Yin
- Lu Sheng
- Bin Liu
- Nenghai Yu
- Xiaogang Wang
- Jing Shao
- Chen Change Loy
author_notes:
- 
- 
- 
- 
- 
- "Corresponding author"
tags: []
categories: []
date: '2018-01-01'
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
projects: ["text-image-retrieval-and-grounding"]
publishDate: '2022-08-26T15:26:28.815336Z'
publication_types:
- '1'
abstract: 'Recognizing visual relationships subject-predicate-object among any pair
  of localized objects is pivotal for image understanding. Previous studies have shown
  remarkable progress in exploiting linguistic priors or external textual information
  to improve the performance. In this work, we investigate an orthogonal perspective
  based on feature interactions. We show that by encouraging deep message propagation
  and interactions between local object features and global predicate features, one
  can achieve compelling performance in recognizing complex relationships without
  using any linguistic priors. To this end, we present two new pooling cells to encourage
  feature interactions: (i) Contrastive ROI Pooling Cell, which has a unique deROI
  pooling that inversely pools local object features to the corresponding area of
  global predicate features. (ii) Pyramid ROI Pooling Cell, which broadcasts global
  predicate features to reinforce local object features. The two cells constitute
  a Spatiality-Context-Appearance Module (SCA-M), which can be further stacked consecutively
  to form our ﬁnal Zoom-Net. We further shed light on how one could resolve ambiguous
  and noisy object and predicate annotations by Intra-Hierarchical trees (IH-tree).
  Extensive experiments conducted on Visual Genome dataset demonstrate the eﬀectiveness
  of our feature-oriented approach compared to state-of-the-art methods (Acc@1 11.42%
  from 8.16%) that depend on explicit modeling of linguistic interactions. We further
  show that SCA-M can be incorporated seamlessly into existing approaches to improve
  the performance by a large margin.'
publication: 'European Conference on Computer Vision (**ECCV**), 2018'
doi: 10.1007/978-3-030-01219-9_20

url_pdf: "https://arxiv.org/abs/1803.08314"
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

---
