---
title: "Robust Stereo Visual-Inertial Odometry Using Nonlinear Optimization"
authors:
- admin
- 白昕晖
- 王英蕾
- 方锐

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2019-08-31T00:00:00Z"
doi: "https://doi.org/10.3390/s19173747"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Sensors, 19(17)*:3747 (2019)"
publication_short: ""

abstract: The fusion of visual and inertial odometry has matured greatly due to the complementarity of the two sensors. However, the use of high-quality sensors and powerful processors in some applications is difficult due to size and cost limitations, and there are also many challenges in terms of robustness of the algorithm and computational efficiency. In this work, we present VIO-Stereo, a stereo visual-inertial odometry (VIO), which jointly combines the measurements of the stereo cameras and an inexpensive inertial measurement unit (IMU). We use nonlinear optimization to integrate visual measurements with IMU readings in VIO tightly. To decrease the cost of computation, we use the FAST feature detector to improve its efficiency and track features by the KLT sparse optical flow algorithm. We also incorporate accelerometer bias into the measurement model and optimize it together with other variables. Additionally, we perform circular matching between the previous and current stereo image pairs in order to remove outliers in the stereo matching and feature tracking steps, thus reducing the mismatch of feature points and improving the robustness and accuracy of the system. Finally, this work contributes to the experimental comparison of monocular visual-inertial odometry and stereo visual-inertial odometry by evaluating our method using the public EuRoC dataset. Experimental results demonstrate that our method exhibits competitive performance with the most advanced techniques.

# Summary. An optional shortened abstract.
summary: this work contributes to the experimental comparison of monocular visual-inertial odometry and stereo visual-inertial odometry by evaluating our method using the public EuRoC dataset. Experimental results demonstrate that our method exhibits competitive performance with the most advanced techniques.

tags:
- Robotics
- VSLAM
- Binocular vision
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.mdpi.com/1424-8220/19/17/3747/htm'
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
  caption: 'The Visual tracking'
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
