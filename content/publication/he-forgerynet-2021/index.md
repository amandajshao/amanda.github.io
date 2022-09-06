---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ForgeryNet: A Versatile Benchmark for Comprehensive Forgery Analysis'
subtitle: ''
summary: ''
authors:
- Yinan He
- Bei Gan
- Siyu Chen
- Yichun Zhou
- Guojun Yin
- Luchuan Song
- Lu Sheng
- Jing Shao
- Ziwei Liu
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- 
-
-
- "Corresponding author"
tags: []
categories: []
date: '2021-06-01'
lastmod: 2022-08-26T23:26:27+08:00
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
projects: ["face-forgery-detection"]
publishDate: '2022-08-26T15:26:27.608609Z'
publication_types:
- '1'
abstract: "The rapid progress of photorealistic synthesis techniques have reached at a critical point where the boundary between real and manipulated images starts to blur. Thus, benchmarking and advancing digital forgery analysis have become a pressing issue. However, existing face forgery datasets either have limited diversity or only support coarse-grained analysis.To counter this emerging threat, we construct the ForgeryNet dataset, an extremely large face forgery dataset with unified annotations in image- and video-level data across four tasks: 1) Image Forgery Classification, including two-way (real/fake), three-way (real/fake with identity-replaced forgery approaches/fake with identity-remained forgery approaches), and n-way (real and 15 respective forgery approaches) classification. 2) Spatial Forgery Localization, which segments the manipulated area of fake images compared to their corresponding real images. 3) Video Forgery Classification, which re-defines the video-level forgery classification with manipulated frames in random positions. This task is important because attackers in real world are free to manipulate any target frame. and 4) Temporal Forgery Localization, to localize the temporal segments which are manipulated. ForgeryNet is by far the largest publicly available deep face forgery dataset in terms of data-scale (2.9 million images, 221,247 videos), manipulations (7 image-level approaches, 8 video-level approaches), perturbations (36 independent and more mixed perturbations) and annotations (6.3 million classification labels, 2.9 million manipulated area annotations and 221,247 temporal forgery segment labels). We perform extensive benchmarking and studies of existing face forensics methods and obtain several valuable observations. We hope that the scale, quality, and variety of our ForgeryNet dataset will foster further research and innovation in the area of face forgery classification, as well as spatial and temporal forgery localization etc."
publication: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (**CVPR**), <span style="color:red">**Oral Presentation**</span>, 2021'
doi: 10.1109/CVPR46437.2021.00434

url_pdf: "https://openaccess.thecvf.com/content/CVPR2021/papers/He_ForgeryNet_A_Versatile_Benchmark_for_Comprehensive_Forgery_Analysis_CVPR_2021_paper.pdf"
url_code:
url_dataset: "https://yinanhe.github.io/projects/forgerynet.html#download"
url_poster:
url_project: "https://yinanhe.github.io/projects/forgerynet.html#"
url_slides:
url_source:
url_video:
---
