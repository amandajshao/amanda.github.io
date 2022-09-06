---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Benchmarking Omni-Vision Representation through the Lens of Visual Realms
subtitle: ''
summary: ''
authors:
- Yuanhan Zhang
- Zhenfei Yin
- Jing Shao
- Ziwei Liu
author_notes:
-
-
- "Corresponding author"
tags: []
categories: []
date: '2022-07-14'
lastmod: 2022-08-26T23:26:33+08:00
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
projects: ["benchmark-and-dataset"]
publishDate: '2022-08-26T15:26:33.293267Z'
publication_types:
- '1'
abstract: 'Though impressive performance has been achieved in specific visual realms (e.g. faces, dogs, and places), an omni-vision representation generalizing to many natural visual domains is highly desirable. But, existing benchmarks are biased and inefficient to evaluate the omni-vision representation -- these benchmarks either only include several specific realms, or cover most realms at the expense of subsuming numerous datasets that have extensive realm overlapping. In this paper, we propose Omni-Realm Benchmark (OmniBenchmark). It includes 21 realm-wise datasets with 7,372 concepts and 1,074,346 images. Without semantic overlapping, these datasets cover most visual realms comprehensively and meanwhile efficiently. In addition, we propose a new supervised contrastive learning framework, namely Relational Contrastive learning (ReCo), for a better omni-vision representation. Beyond pulling two instances from the same concept closer -- the typical supervised contrastive learning framework -- ReCo also pulls two instances from the same semantic realm closer, encoding the semantic relation between concepts, and facilitating omni-vision representation learning. We benchmark ReCo and other advances in omni-vision representation studies that are different in architectures (from CNNs to transformers) and in learning paradigms (from supervised learning to self-supervised learning) on OmniBenchmark. We illustrate the superior of ReCo to other supervised contrastive learning methods and reveal multiple practical observations to facilitate future research.'
publication: European Conference on Computer Vision (**ECCV**), 2022

url_pdf: http://arxiv.org/abs/2207.07106
url_project: https://zhangyuanhan-ai.github.io/OmniBenchmark/

---
