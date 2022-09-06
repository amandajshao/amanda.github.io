---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ERGO: Event Relational Graph Transformer for Document-level Event Causality
  Identification'
subtitle: ''
summary: ''
authors:
- Meiqi Chen
- Yixin Cao
- Kunquan Deng
- Mukai Li
- Kun Wang
- Jing Shao
- Yan Zhang
tags: ["Knowledge Graph", "Event Causality Identification"]
categories: []
date: '2022-04-15'
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
projects: []
publishDate: '2022-08-26T15:26:32.789890Z'
publication_types:
- '3'
abstract: 'Document-level Event Causality Identification (DECI) aims to identify causal relations between event pairs in a document. It poses a great challenge of across-sentence reasoning without clear causal indicators. In this paper, we propose a novel Event Relational Graph TransfOrmer (ERGO) framework for DECI, which improves existing state-of-the-art (SOTA) methods upon two aspects. First, we formulate DECI as a node classification problem by constructing an event relational graph, without the needs of prior knowledge or tools. Second, ERGO seamlessly integrates event-pair relation classification and global inference, which leverages a Relational Graph Transformer (RGT) to capture the potential causal chain. Besides, we introduce edge-building strategies and adaptive focal loss to deal with the massive false positives caused by common spurious correlation. Extensive experiments on two benchmark datasets show that ERGO significantly outperforms previous SOTA methods (13.1% F1 gains on average). We have conducted extensive quantitative analysis and case studies to provide insights for future research directions (Section 4.8).'
publication: '*CoRR*'

url_pdf: "https://arxiv.org/abs/2204.07434v1"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:
---
