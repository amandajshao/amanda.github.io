---
widget: slider  # Use the Slider widget as this page section
weight: 1  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '600px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 'INTERN: A New Learning Paradigm Towards General Vision'
      content: "Our new learning paradigm, INTERN, aims to systematically solve bottlenecks in recent *scenario-specifc* vision intelligence systems. The model being trained by INTERN will develop strong generalizability towards various vision tasks."
      align: left
      background:
        position: center
        brightness: 0.5
        media: sider/intern.png
        fit: cover
      link:
        text: Read More
        url: ../publication/shao-intern-2021
      
    - title: 'Benchmarking Omni-Vision Representation through the Lens of Visual Realms'
      content: Omni-Realm Benchmark (OmniBenchmark) is a **diverse** (21 semantic realm-wise datasets) and **concise** (realm-wise datasets have no concepts overlapping) benchmark for evaluating pre-trained model generalization across semantic super-concepts/realms.
      align: left
      background:
        position: center
        brightness: 0.5
        media: sider/omnibenchmark.jpeg
        url: 
        fit: cover
      link:
        text: Read More
        url: ../publication/zhang-benchmarking-2022
  
    - title: 'X-Learner: Learning Cross Sources and Tasks for Universal Visual Representation'
      content: "Jointly learning from heterogeneous tasks and multiple data sources contributes to universal visual representation, leading to better transferring results of various downstream tasks."
      align: left
      background:
        position: center
        brightness: 0.5
        media: sider/xlearner.png
        url: 
        fit: cover
      link:
        text: Read More
        url: ../publication/he-x-learner-2022   
    
    - title: 'ForgeryNet: A Versatile Benchmark for Comprehensive Forgery Analysis'
      content: "We host the [ForgeryNet Challenge 2021](https://competitions.codalab.org/competitions/33386) in [ICCV 2021, The 3rd Workshop on Sensing, Understanding and Synthesizing Humans](https://yinanhe.github.io/projects/forgerynet.html#)."
      align: left
      background:
        position: center
        brightness: 0.5
        media: sider/forgerynet.png
        url: 
        fit: cover
      link:
        text: Read More
        url: ../publication/he-forgerynet-2021  
    
    - title: 'MMEKG: Multi-modal Event Knowledge Graph towards Universal Representation across Modalities'
      content: "MMEKG unifies different modalities of knowledge via events, which complement and disambiguate each other."
      align: left
      background:
        position: center
        brightness: 0.5
        media: sider/mmekg.png
        url: 
        fit: cover
      link:
        text: Read More
        url: ../publication/ma-mmekg-2022   

    - title: 'Prompt for Extraction? PAIE: Prompting Argument Interaction for Event Argument Extraction'
      content: "In this paper, we propose an effective yet efficient model PAIE for both sentence-level and document-level Event Argument Extraction (EAE), which also generalizes well when there is a lack of training data."
      align: left
      background:
        position: center
        brightness: 0.5
        media: sider/paie.png
        url: 
        fit: cover
      link:
        text: Read More
        url: ../publication/ma-prompt-2022  

    - title: 'CelebA-Spoof: Large-Scale Face Anti-spoofing Dataset with Rich Annotations'
      content: "CelebA-Spoof is a large-scale face anti-spoofing dataset that has 625,537 images from 10,177 subjects, which includes 43 rich attributes on face, illumination, environment and spoof types."
      align: left
      background:
        position: center
        brightness: 0.5
        media: sider/celebaspoof.png
        url: 
        fit: cover
      link:
        text: Read More
        url: ../publication/vedaldi-celeba-spoof-2020

---