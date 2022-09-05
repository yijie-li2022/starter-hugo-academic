---
title: 'AMDCNet: An attentional multi-directional convolutional network for stereo
matching'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hewei Wang
  - admin
  - Xishi Jia
  - Shaofan Wang
  - Muhammad Salman Pathan
  - Soumyabrata Dev

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-05-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Displays*
publication_short: In *Displays*

abstract: Stereo matching refers to finding the correspondence of a point in the real world between two different storage mediums (e.g., intensity images, depth images, three-dimensional points). There are existing stereo matching methods in the literature, but they exhibit two shortcomings. Firstly, during the feature region extraction of stereo matching, these methods require measuring the distance of regions, but measuring the texture distribution of the region is difficult and might lead to the failure of matching. Secondly, the templates used in these methods are rectangles with a fixed size, while most of the natural images exhibit rich information and are more suitable for flexible templates. In this paper, we propose an attentional multi-directional convolutional network (AMDCNet) for circumventing these issues. Our AMDCNet approach consists of three stages-- extract the visual sensitivity factor, construct the multi-directional aggregation template and utilize left–right consistency detection to optimize. We evaluate our approach using standard images in the Middlebury test dataset, Scene Flow and KITTI 2015. Experimental results show that AMDCNet can reduce the mismatch rate, and also show significant improvement in accuracy compared with some classical method. In some scenarios, it surpasses some advanced methods based on deep learning. The model code, dataset, and results of the experiments in this paper are available at- https://github.com/WangHewei16/Attentional-Multi-Directional-Convolution-Network.

# Summary. An optional shortened abstract.
summary: Our AMDCNet approach consists of three stages– extract the visual sensitivity factor, construct the multi-directional aggregation template and utilize left–right consistency detection to optimize. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/SCI-Elsevier-Displays-AMDCNet.pdf'
url_code: 'https://github.com/WangHewei16/Attentional-Multi-Directional-Convolution-Network'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overall Pipline of AMDCNet'
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
