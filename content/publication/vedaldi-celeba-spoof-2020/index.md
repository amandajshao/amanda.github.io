---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'CelebA-Spoof: Large-Scale Face Anti-spoofing Dataset with Rich Annotations'
subtitle: ''
summary: '**CelebA-Spoof** is a large-scale face anti-spoofing dataset that has 625,537 images from 10,177 subjects, which includes 43 rich attributes on face, illumination, environment and spoof types. Live images are selected from the CelebA dataset. We collect and annotate spoof images for CelebA-Spoof. Among 43 rich attributes, 40 attributes belong to live images including all facial components and accessories such as skin, nose, eyes, eyebrows, lip, hair, hat, eyeglass. 3 attributes belong to spoof images including spoof types, environments and illumination conditions. **CelebA-Spoof** can be used to train and evaluate algorithms of face anti-spoofing, face presentation attacks, and robustness/security research.'
authors:
- Yuanhan Zhang
- ZhenFei Yin
- Yidong Li
- Guojun Yin
- Junjie Yan
- Jing Shao
- Ziwei Liu
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: []
categories: []
date: '2020-10-01'
lastmod: 2022-08-26T23:26:30+08:00
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
projects: ["face-antispoofing"]
publishDate: '2022-08-26T15:26:30.091318Z'
publication_types:
- '1'
abstract: 'As facial interaction systems are prevalently deployed, security and reliability
  of these systems become a critical issue, with substantial research eﬀorts devoted.
  Among them, face anti-spooﬁng emerges as an important area, whose objective is to
  identify whether a presented face is live or spoof. Though promising progress has
  been achieved, existing works still have diﬃculty in handling complex spoof attacks
  and generalizing to real-world scenarios. The main reason is that current face anti-spooﬁng
  datasets are limited in both quantity and diversity. To overcome these obstacles,
  we contribute a large-scale face anti-spooﬁng dataset, CelebA-Spoof, with the following
  appealing properties: 1) Quantity: CelebA-Spoof comprises of 625,537 pictures of
  10,177 subjects, signiﬁcantly larger than the existing datasets. 2) Diversity: The
  spoof images are captured from 8 scenes (2 environments * 4 illumination conditions)
  with more than 10 sensors. 3) Annotation Richness: CelebA-Spoof contains 10 spoof
  type annotations, as well as the 40 attribute annotations inherited from the original
  CelebA dataset. Equipped with CelebA-Spoof, we carefully benchmark existing methods
  in a uniﬁed multi-task framework, Auxiliary Information Embedding Network (AENet),
  and reveal several valuable observations. Our key insight is that, compared with
  the commonly-used binary supervision or mid-level geometric representations, rich
  semantic annotations as auxiliary tasks can greatly boost the performance and generalizability
  of face anti-spooﬁng across a wide range of spoof attacks. Through comprehensive
  studies, we show that CelebA-Spoof serves as an eﬀective training data source. Models
  trained on CelebA-Spoof (without ﬁne-tuning) exhibit state-of-the-art performance
  on standard benchmarks such as CASIA-MFSD. The datasets are available at https://github.com/Davidzhangyuanhan/CelebA-Spoof
  .'
publication: 'European Conference on Computer Vision (**ECCV**), 2020'
doi: 10.1007/978-3-030-58610-2_5

url_pdf: "https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570069.pdf"
url_code: 
url_dataset: "https://github.com/ZhangYuanhan-AI/CelebA-Spoof"
url_poster:
url_project: "https://mmlab.ie.cuhk.edu.hk/projects/CelebA/CelebA_Spoof.html"
url_slides:
url_source:
url_video: "https://www.youtube.com/watch?v=A7XjSg5srvI&t=4s"

---
