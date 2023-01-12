---
title: 'BSANet: A Bilateral Segregation and Aggregation
Network for Real-time Sky/Cloud Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hewei Wang
  - Shaofan Wang
  - Yee Hui Lee
  - Soumyabrata Dev

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-11-15T00:00:00Z'
doi: 'http://dx.doi.org/10.13140/RG.2.2.35512.62723/1'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-19T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Preprint*'
publication_short: '*Preprint*'

abstract: 'Segmenting cloud from intensity images is an essential research topic at the intersection of atmospheric science and computer vision, which plays a vital role in weather forecasts, environmental monitoring, and climate evolution analysis. The ground-based sky/cloud image segmentation can help to extract the cloud from the original image and analyze the shape or additional features. The early approaches are mainly based on traditional methods and have limited segmentation performance on both day and night instances. After the advent of deep learning, many researches have been conducted to adopt convolutional neural networks (CNNs) to perform the end-to-end training of a segmentation model. However, these early CNNbased designs usually use a great number of parameters to guarantee accuracy, leading to a slow inference speed. In this paper, we introduced a novel sky/cloud segmentation network named Bilateral Segregation and Aggregation Network (BSANet) with 16.37 MBytes, which can reduce 70.68% of model size and achieve almost the same performance as the state-of-theart method. After the deployment via TensorRT, BSANet-large configuration can achieve 392 fps in FP16, while BSANet-lite can achieve 1390 fps. Additionally, we proposed a novel and fast pretraining strategy for sky/cloud segmentation which can improve the accuracy of segmentation when ImageNet pre-training is not available. In the spirit of reproducible research, the model code, dataset, and results of the experiments in this paper are available at: https://github.com/Att100/BSANet-cloudseg.'

# Summary. An optional shortened abstract.
summary: 'In this paper, we introduced a novel sky/cloud segmentation network named Bilateral Segregation and Aggregation Network (BSANet) with 16.37 MBytes, which can reduce 70.68% of model size and achieve almost the same performance as the state-of-theart method.'

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/BSANet_cloudseg_2022.pdf'
url_code: 'https://github.com/Att100/BSANet-cloudseg'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overall Pipline of BSANet'
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
