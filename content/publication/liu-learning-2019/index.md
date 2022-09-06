---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning to Predict Layout-to-image Conditional Convolutions for Semantic Image
  Synthesis
subtitle: ''
summary: ''
authors:
- Xihui Liu
- Guojun Yin
- Jing Shao
- Xiaogang Wang
- hongsheng Li
tags: []
categories: []
date: '2019-12-01'
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
projects: ["image-and-video-generation"]
publishDate: '2022-08-26T15:26:30.474200Z'
publication_types:
- '1'
abstract: Semantic image synthesis aims at generating photorealistic images from semantic
  layouts. Previous approaches with conditional generative adversarial networks (GAN)
  show state-of-the-art performance on this task, which either feed the semantic label
  maps as inputs to the generator, or use them to modulate the activations in normalization
  layers via affine transformations. We argue that convolutional kernels in the generator
  should be aware of the distinct semantic labels at different locations when generating
  images. In order to better exploit the semantic layout for the image generator,
  we propose to predict convolutional kernels conditioned on the semantic label map
  to generate the intermediate feature maps from the noise maps and eventually generate
  the images. Moreover, we propose a feature pyramid semantics-embedding discriminator,
  which is more effective in enhancing fine details and semantic alignments between
  the generated images and the input semantic layouts than previous multi-scale discriminators.
  We achieve state-of-the-art results on both quantitative metrics and subjective
  evaluation on various semantic segmentation datasets, demonstrating the effectiveness
  of our approach.
publication: 'Advances in Neural Information Processing Systems (**NeurIPS**), 2019'

url_pdf: "https://arxiv.org/pdf/1910.06809.pdf"
url_code: "https://github.com/xh-liu/CC-FPSE"
url_dataset:
url_poster:
url_project:
url_slides: "https://drive.google.com/file/d/1m3JKSUotm6sRImak_qjwBMtMtd037XeK/view"
url_source:
url_video:

---
