---
title: 'SYGNet: A SVD-YOLO based GhostNet for Real-time Driving Scene Parsing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hewei Wang
  - Bolun Zhu
  - admin
  - Kaiwen Gong
  - Ziyuan Wen
  - Shaofan Wang
  - Soumyabrata Dev

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-06-15T00:00:00Z'
doi: 'http://dx.doi.org/10.1109/ICIP46576.2022.9897534'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: '*29th IEEE International Conference on Image Processing (ICIP)*'
publication_short: '*29th IEEE International Conference on Image Processing (ICIP)*'

abstract: In this paper, we propose SYGNet to strengthen the scene parsing ability of autonomous driving under complicated road conditions. The SYGNet includes feature extraction component and SVD-YOLO GhostNet component. The SVD-YOLO GhostNet component combines Singular Value Decomposition (SVD), You Only Look Once (YOLO) and GhostNet. In the feature extraction component, we propose an algorithm based on VoxelNet to extract point cloud features and image features. In SVD-YOLO GhostNet component, the image data is decomposed by SVD, and we obtain data with stronger spatial and environmental characteristics. YOLOv3 is used to obtain the future map, then convert to GhostNet, which is used to realize the real-time scene parsing by utilizing fewer filters to generate some intrinsic feature maps. We use KITTI dataset to perform our experiments and the results show that the SYGNet is more robust and can further enhance the accuracy of real-time driving scene parsing.

# Summary. An optional shortened abstract.
summary: We propose SYGNet to strengthen the scene parsing ability of autonomous driving under complicated road conditions.  

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/IEEE-ICIP pp.2701-2705.pdf'
url_code: 'https://github.com/WangHewei16/SYGNet-for-Real-time-Driving-Scene-Parsing'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overall Pipline of SYGNet'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---
