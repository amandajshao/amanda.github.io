---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'CAMP: Cross-Modal Adaptive Message Passing for Text-Image Retrieval'
subtitle: ''
summary: ''
authors:
- Zihao Wang
- Xihui Liu
- Hongsheng Li
- Lu Sheng
- Junjie Yan
- Xiaogang Wang
- Jing Shao
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: []
categories: []
date: '2019-10-01'
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
publishDate: '2022-08-26T15:26:28.298788Z'
publication_types:
- '1'
abstract: Text-image cross-modal retrieval is a challenging task in the field of language
  and vision. Most previous approaches independently embed images and sentences into
  a joint embedding space and compare their similarities. However, previous approaches
  rarely explore the interactions between images and sentences before calculating
  similarities in the joint space. Intuitively, when matching between images and sentences,
  human beings would alternatively attend to regions in images and words in sentences,
  and select the most salient information considering the interaction between both
  modalities. In this paper, we propose Cross-modal Adaptive Message Passing (CAMP),
  which adaptively controls the information flow for message passing across modalities.
  Our approach not only takes comprehensive and fine-grained cross-modal interactions
  into account, but also properly handles negative pairs and irrelevant information
  with an adaptive gating scheme. Moreover, instead of conventional joint embedding
  approaches for text-image matching, we infer the matching score based on the fused
  features, and propose a hardest negative binary cross-entropy loss for training.
  Results on COCO and Flickr30k significantly surpass state-of-the-art methods, demonstrating
  the effectiveness of our approach.
publication: 'IEEE/CVF International Conference on Computer Vision (**ICCV**), 2019'
doi: 10.1109/ICCV.2019.00586

url_pdf: "https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_CAMP_Cross-Modal_Adaptive_Message_Passing_for_Text-Image_Retrieval_ICCV_2019_paper.pdf"
url_code: "https://github.com/ZihaoWang-CV/CAMP_iccv19"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

---
