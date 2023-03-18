---
title: "Phase aberration compensation via deep learning in digital holographic microscopy"
authors:
- admin
- 方锐
- 罗煜
- 刘琦
- Shiliang Wang
- 周旭
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-05-17T00:00:00Z"
doi: "https://doi.org/10.1088/1361-6501/ac0216"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Measurement Science and Technology, 32*:105203 (2021)"
publication_short: ""

abstract: Digital holographic microscopy (DHM), a quantitative phase-imaging technology, has been widely used in various applications. Phase-aberration compensation in off-axis DHM is vital to reconstruct topographical images with high precision, especially for microstructures with a small background or a dense phase distribution. We propose a numerical method based on deep learning combined with DHM. First, a convolutional neural network (CNN) recognizes and segments the sample and the background area of the hologram. Zernike polynomial fitting is then executed on the extracted background area. Finally, the whole process of phase-aberration compensation is automatically performed. To obtain a robust and accurate deep-learning model for hologram segmentation, we collected many holograms corresponding to several samples that had different morphological characteristics. The experimental results confirm that the trained CNN can accurately segment the sample from the background area of the hologram, and that this method is applicable and effective in off-axis DHM.

# Summary. An optional shortened abstract.
summary: The experimental results confirm that the trained CNN can accurately segment the sample from the background area of the hologram, and that this method is applicable and effective in off-axis DHM.
tags:
- 数字全息显微
- 深度学习
- U-net
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Figure abstract'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: /content/project/NSFC-2020/index.md

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}


