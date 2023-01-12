---
title: 'UCloudNet: A Residual U-Net with Deep Supervision for Sky/Cloud Image Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hewei Wang
  - Shaofan Wang
  - Soumyabrata Dev

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-03-10T00:00:00Z'
doi: 'http://dx.doi.org/10.13140/RG.2.2.25638.80969'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Preprint*'
publication_short: '*Preprint*'

abstract: "Recently, there is a growing interest in the use of ground-based sky cameras for meteorology applications. The seg-mentation of sky/cloud images obtained from these sky cameras offers us great insights into the cloud coverage computation and understanding various atmospheric events. Most of the existing research in sky/cloud image segmentation are based on traditional computer vision methods, including the use of color features and gradient variation in the images. With the development of deep learning architectures, convolutional neural networks (CNNs) have been widely used for sky/cloud image segmentation. However, CNNs require larger training time and higher number of epochs to converge. This limits its widespread use on onboard sky camera's computing systems. In this paper, we introduce a residual U-Net with deep supervision for cloud segmentation which provides better performance than other CNN-based approaches, and with less training consumption. Our proposed model achieves the highest F-score value as compared to the state-of-the-art cloud segmentation techniques. In the spirit of reproducible research, the model code, dataset, and results of the experiments in this paper are available at: https://github.com/Att100/UCloudNet."

# Summary. An optional shortened abstract.
summary: 'In this paper, we introduce a residual U-Net with deep supervision for cloud segmentation which provides better performance than other CNN-based approaches, and with less training consumption.'

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/UCloudNet_cloudseg_2022.pdf'
url_code: 'https://github.com/Att100/UCloudNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overall Pipline of UCloudNet'
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
