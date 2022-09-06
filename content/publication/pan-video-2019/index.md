---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Video Generation From Single Semantic Label Map
subtitle: ''
summary: ''
authors:
- Junting Pan
- Chengyu Wang
- Xu Jia
- Jing Shao
- Lu Sheng
- Junjie Yan
- Xiaogang Wang
author_notes:
-
- 
- 
- 
- "Corresponding author"
tags: []
categories: []
date: '2019-06-01'
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
projects: ["image-and-video-generation"]
publishDate: '2022-08-26T15:26:28.426957Z'
publication_types:
- '1'
abstract: This paper proposes the novel task of video generation conditioned on a
  SINGLE semantic label map, which provides a good balance between ﬂexibility and
  quality in the generation process. Different from typical end-to-end approaches,
  which model both scene content and dynamics in a single step, we propose to decompose
  this difﬁcult task into two sub-problems. As current image generation methods do
  better than video generation in terms of detail, we synthesize high quality content
  by only generating the ﬁrst frame. Then we animate the scene based on its semantic
  meaning to obtain temporally coherent video, giving us excellent results overall.
  We employ a cVAE for predicting optical ﬂow as a beneﬁcial intermediate step to
  generate a video sequence conditioned on the initial single frame. A semantic label
  map is integrated into the ﬂow prediction module to achieve major improvements in
  the image-to-video generation process. Extensive experiments on the Cityscapes dataset
  show that our method outperforms all competing methods. The source code will be
  released on https://github.com/junting/seg2vid.
publication: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (**CVPR**), 2019'
doi: 10.1109/CVPR.2019.00385

url_pdf: "https://openaccess.thecvf.com/content_CVPR_2019/papers/Pan_Video_Generation_From_Single_Semantic_Label_Map_CVPR_2019_paper.pdf"
url_code: "https://github.com/junting/seg2vid"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

---
