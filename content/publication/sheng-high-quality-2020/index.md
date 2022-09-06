---
# Documentation: https://wowchemy.com/docs/managing-content/

title: High-Quality Video Generation from Static Structural Annotations
subtitle: ''
summary: ''
authors:
- Lu Sheng
- Junting Pan
- Jiaming Guo
- Jing Shao
- Chen Change Loy
tags:
- Conditioned generative model
- Image and video synthesis
- Motion prediction and estimatiovn
- Unsupervised learning
categories: []
date: '2020-05-28'
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
publishDate: '2022-08-26T15:26:28.047791Z'
publication_types:
- '2'
abstract: 'This paper proposes a novel unsupervised video generation that is conditioned
  on a single structural annotation map, which in contrast to prior conditioned video
  generation approaches, provides a good balance between motion flexibility and visual
  quality in the generation process. Different from end-to-end approaches that model
  the scene appearance and dynamics in a single shot, we try to decompose this difficult
  task into two easier sub-tasks in a divide-and-conquer fashion, thus achieving remarkable
  results overall. The first sub-task is an image-to-image (I2I) translation task
  that synthesizes high-quality starting frame from the input structural annotation
  map. The second image-to-video (I2V) generation task applies the synthesized starting
  frame and the associated structural annotation map to animate the scene dynamics
  for the generation of a photorealistic and temporally coherent video. We employ
  a cycle-consistent flow-based conditioned variational autoencoder to capture the
  long-term motion distributions, by which the learned bi-directional flows ensure
  the physical reliability of the predicted motions and provide explicit occlusion
  handling in a principled manner. Integrating structural annotations into the flow
  prediction also improves the structural awareness in the I2V generation process.
  Quantitative and qualitative evaluations over the autonomous driving and human action
  datasets demonstrate the effectiveness of the proposed approach over the state-of-the-art
  methods. The code has been released: https://github.com/junting/seg2vid.'
publication: 'International Journal of Computer Vision (**IJCV**), 2020'
doi: 10.1007/s11263-020-01334-x

url_pdf: "https://link.springer.com/article/10.1007/s11263-020-01334-x"
url_code: "https://github.com/junting/seg2vid"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

---
