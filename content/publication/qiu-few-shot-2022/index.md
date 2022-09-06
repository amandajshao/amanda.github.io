---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Few-shot Forgery Detection via Guided Adversarial Interpolation
subtitle: ''
summary: ''
authors:
- Haonan Qiu
- Siyu Chen
- Bei Gan
- Kun Wang
- Huafeng Shi
- Jing Shao
- Ziwei Liu
tags: []
categories: []
date: '2022-04-12'
lastmod: 2022-08-26T23:26:32+08:00
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
projects: ["face-forgery-detection"]
publishDate: '2022-08-26T15:26:32.661790Z'
publication_types:
- '3'
abstract: 'Realistic visual media synthesis is becoming a critical societal issue with the surge of face manipulation models; new forgery approaches emerge at an unprecedented pace. Unfortunately, existing forgery detection methods suffer significant performance drops when applied to novel forgery approaches. In this work, we address the few-shot forgery detection problem by designing a comprehensive benchmark based on coverage analysis among various forgery approaches, and proposing Guided Adversarial Interpolation (GAI). Our key insight is that there exist transferable distribution characteristics among different forgery approaches with the majority and minority classes. Specifically, we enhance the discriminative ability against novel forgery approaches via adversarially interpolating the artifacts of the minority samples to the majority samples under the guidance of a teacher network. Unlike the standard re-balancing method which usually results in over-fitting to minority classes, our method simultaneously takes account of the diversity of majority information as well as the significance of minority information. Extensive experiments demonstrate that our GAI achieves state-of-the-art performances on the established few-shot forgery detection benchmark. Notably, our method is also validated to be robust to choices of majority and minority forgery approaches.'
publication: '*CoRR*'

url_pdf: "https://arxiv.org/abs/2204.05905"
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

---
