---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Prompt for Extraction? PAIE: Prompting Argument Interaction for Event Argument
  Extraction'
subtitle: ''
summary: ''
authors:
- Yubo Ma
- Zehao Wang
- Yixin Cao
- Mukai Li
- Meiqi Chen
- Kun Wang
- Jing Shao
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Corresponding author"
tags: []
categories: []
date: '2022-05-01'
lastmod: 2022-08-26T23:26:29+08:00
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
projects: ["knowledge-graph"]
publishDate: '2022-08-26T15:26:29.584431Z'
publication_types:
- '1'
abstract: In this paper, we propose an effective yet efficient model PAIE for both
  sentence-level and document-level Event Argument Extraction (EAE), which also generalizes
  well when there is a lack of training data. On the one hand, PAIE utilizes prompt
  tuning for extractive objectives to take the best advantages of Pre-trained Language
  Models (PLMs). It introduces two span selectors based on the prompt to select start/end
  tokens among input texts for each role. On the other hand, it captures argument
  interactions via multi-role prompts and conducts joint optimization with optimal
  span assignments via a bipartite matching loss. Also, with a flexible prompt design,
  PAIE can extract multiple arguments with the same role instead of conventional heuristic
  threshold tuning. We have conducted extensive experiments on three benchmarks, including
  both sentence- and document-level EAE. The results present promising improvements
  from PAIE (3.5% and 2.3% F1 gains in average on three benchmarks, for PAIE-base
  and PAIE-large respectively). Further analysis demonstrates the efficiency, generalization
  to few-shot settings, and effectiveness of different extractive prompt tuning strategies.
  Our code is available at https://github.com/mayubo2333/PAIE.
publication: ' Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers) (**ACL Long Papers**), 2022'
doi: 10.18653/v1/2022.acl-long.466

url_pdf: "https://aclanthology.org/2022.acl-long.466.pdf"
url_code: "https://github.com/mayubo2333/PAIE"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

---
