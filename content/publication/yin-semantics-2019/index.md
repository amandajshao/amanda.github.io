---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Semantics Disentangling for Text-To-Image Generation
subtitle: ''
summary: ''
authors:
- Guojun Yin
- Bin Liu
- Lu Sheng
- Nenghai Yu
- Xiaogang Wang
- Jing Shao
author_notes:
-
-
- "Corresponding author"
tags:
- Image and Video Synthesis
- Vision + Language
categories: []
date: '2019-06-01'
lastmod: 2022-08-26T23:26:29+08:00
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
projects: ["image-and-video-generation"]
publishDate: '2022-08-26T15:26:29.198881Z'
publication_types:
- '1'
abstract: Synthesizing photo-realistic images from text descriptions is a challenging
  problem. Previous studies have shown remarkable progresses on visual quality of
  the generated images. In this paper, we consider semantics from the input text descriptions
  in helping render photo-realistic images. However, diverse linguistic expressions
  pose challenges in extracting consistent semantics even they depict the same thing.
  To this end, we propose a novel photo-realistic text-to-image generation model that
  implicitly disentangles semantics to both fulfill the high-level semantic consistency
  and low-level semantic diversity. To be specific, we design (1) a Siamese mechanism
  in the discriminator to learn consistent high-level semantics, and (2) a visual-semantic
  embedding strategy by semantic-conditioned batch normalization to find diverse low-level
  semantics. Extensive experiments and ablation studies on CUB and MS-COCO datasets
  demonstrate the superiority of the proposed method in comparison to state-of-the-art
  methods.
publication: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (**CVPR**), <span style="color:red">**Oral Presentation**</span>, 2019'
doi: 10.1109/CVPR.2019.00243

url_pdf: "https://openaccess.thecvf.com/content_CVPR_2019/papers/Yin_Semantics_Disentangling_for_Text-To-Image_Generation_CVPR_2019_paper.pdf"
url_project: "https://gjyin91.github.io/projects/sdgan.html"

---
