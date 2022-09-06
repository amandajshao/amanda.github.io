---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Connectivity of Neural Networks from a Topological Perspective
subtitle: ''
summary: ''
authors:
- Kun Yuan
- Quanquan Li
- Jing Shao
- Junjie Yan
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: []
categories: []
date: '2020-10-01'
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
projects: ["network"]
publishDate: '2022-08-26T15:26:30.215272Z'
publication_types:
- '1'
abstract: Seeking eﬀective neural networks is a critical and practical ﬁeld in deep
  learning. Besides designing the depth, type of convolution, normalization, and nonlinearities,
  the topological connectivity of neural networks is also important. Previous principles
  of rule-based modular design simplify the diﬃculty of building an eﬀective architecture,
  but constrain the possible topologies in limited spaces. In this paper, we attempt
  to optimize the connectivity in neural networks. We propose a topological perspective
  to represent a network into a complete graph for analysis, where nodes carry out
  aggregation and transformation of features, and edges determine the ﬂow of information.
  By assigning learnable parameters to the edges which reﬂect the magnitude of connections,
  the learning process can be performed in a diﬀerentiable manner. We further attach
  auxiliary sparsity constraint to the distribution of connectedness, which promotes
  the learned topology focus on critical connections. This learning process is compatible
  with existing networks and owns adaptability to larger search spaces and diﬀerent
  tasks. Quantitative results of experiments reﬂect the learned connectivity is superior
  to traditional rule-based ones, such as random, residual and complete. In addition,
  it obtains signiﬁcant improvements in image classiﬁcation and object detection without
  introducing excessive computation burden.
publication: 'European Conference on Computer Vision (**ECCV**), 2020'
doi: 10.1007/978-3-030-58589-1_44

url_pdf: "https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660732.pdf"

---
