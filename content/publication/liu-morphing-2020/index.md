---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Morphing and Sampling Network for Dense Point Cloud Completion
subtitle: ''
summary: ''
authors:
- Minghua Liu
- Lu Sheng
- Sheng Yang
- Jing Shao
- Shi-Min Hu
tags: []
categories: []
date: '2020-04-01'
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
projects: []
publishDate: '2022-08-26T15:26:28.174916Z'
publication_types:
- '1'
abstract: 3D point cloud completion, the task of inferring the complete geometric
  shape from a partial point cloud, has been attracting attention in the community.
  For acquiring high-fidelity dense point clouds and avoiding uneven distribution,
  blurred details, or structural loss of existing methods' results, we propose a novel
  approach to complete the partial point cloud in two stages. Specifically, in the
  first stage, the approach predicts a complete but coarse-grained point cloud with
  a collection of parametric surface elements. Then, in the second stage, it merges
  the coarse-grained prediction with the input point cloud by a novel sampling algorithm.
  Our method utilizes a joint loss function to guide the distribution of the points.
  Extensive experiments verify the effectiveness of our method and demonstrate that
  it outperforms the existing methods in both the Earth Mover's Distance (EMD) and
  the Chamfer Distance (CD).
publication: 'AAAI Conference on Artificial Intelligence (**AAAI**), 2020'
doi: 10.1609/aaai.v34i07.6827

url_pdf: "https://ojs.aaai.org/index.php/AAAI/article/view/6827"
url_code: "https://github.com/Colin97/MSN-Point-Cloud-Completion"
url_dataset: "https://drive.google.com/drive/folders/1oYOT8fTUyj6_db9f4cYiKFqP9LPEG5nH"
url_poster:
url_project:
url_slides:
url_source:
url_video:

---
