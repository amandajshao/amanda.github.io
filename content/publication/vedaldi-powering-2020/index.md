---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Powering One-Shot Topological NAS with Stabilized Share-Parameter Proxy
subtitle: ''
summary: ''
authors:
- Ronghao Guo
- Chen Lin
- Chuming Li
- Keyu Tian
- Ming Sun
- Lu Sheng
- Junjie Yan
author_notes:
- "Equal contribution"
- "Equal contribution"
- 
- 
- 
- "Corresponding author"
tags: []
categories: []
date: '2020-10-01'
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
projects: ["network"]
publishDate: '2022-08-26T15:26:27.918192Z'
publication_types:
- '1'
abstract: One-shot NAS method has attracted much interest from the research community
  due to its remarkable training eﬃciency and capacity to discover high performance
  models. However, the search spaces of previous one-shot based works usually relied
  on hand-craft design and were short for ﬂexibility on the network topology. In this
  work, we try to enhance the one-shot NAS by exploring high-performing network architectures
  in our large-scale Topology Augmented Search Space (i.e, over 3.4 × 1010 diﬀerent
  topological structures). Speciﬁcally, the diﬃculties for architecture searching
  in such a complex space has been eliminated by the proposed stabilized share-parameter
  proxy, which employs Stochastic Gradient Langevin Dynamics to enable fast shared
  parameter sampling, so as to achieve stabilized measurement of architecture performance
  even in search space with complex topological structures. The proposed method, namely
  Stablized Topological Neural Architecture Search (ST-NAS), achieves state-of-the-art
  performance under Multiply-Adds (MAdds) constraint on ImageNet. Our lite model ST-NAS-A
  achieves 76.4% top-1 accuracy with only 326M MAdds. Our moderate model STNAS-B achieves
  77.9% top-1 accuracy just required 503M MAdds. Both of our models oﬀer superior
  performances in comparison to other concurrent works on one-shot NAS.
publication: 'European Conference on Computer Vision (**ECCV**), 2020'
doi: 10.1007/978-3-030-58568-6_37

url_pdf: "https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590613.pdf"

---
