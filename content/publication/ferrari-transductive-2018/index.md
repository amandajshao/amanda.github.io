---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Transductive Centroid Projection for Semi-supervised Large-Scale Recognition
subtitle: ''
summary: ''
authors:
- Yu Liu
- Guanglu Song
- Jing Shao
- Xiao Jin
- Xiaogang Wang
tags: []
categories: []
date: '2018-09-06'
lastmod: 2022-08-26T23:26:30+08:00
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
publishDate: '2022-08-26T15:26:30.859591Z'
publication_types:
- '1'
abstract: Conventional deep semi-supervised learning methods, such as recursive clustering
  and training process, suﬀer from cumulative error and high computational complexity
  when collaborating with Convolutional Neural Networks. To this end, we design a
  simple but eﬀective learning mechanism that merely substitutes the last fully-connected
  layer with the proposed Transductive Centroid Projection (TCP) module. It is inspired
  by the observation of the weights in the ﬁnal classiﬁcation layer (called anchors)
  converge to the central direction of each class in hyperspace. Speciﬁcally, we design
  the TCP module by dynamically adding an ad hoc anchor for each cluster in one mini-batch.
  It essentially reduces the probability of the inter-class conﬂict and enables the
  unlabelled data functioning as labelled data. We inspect its eﬀectiveness with elaborate
  ablation study on seven public face/person classiﬁcation benchmarks. Without any
  bells and whistles, TCP can achieve signiﬁcant performance gains over most state-of-the-art
  methods in both fully-supervised and semi-supervised manners.
publication: 'European Conference on Computer Vision (**ECCV**), 2018'
doi: 10.1007/978-3-030-01228-1_5

url_pdf: "https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Yu_Liu_Transductive_Centroid_Projection_ECCV_2018_paper.pdf"
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

  
---
