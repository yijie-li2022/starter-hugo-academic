---
title: 'DAANet: Dual Attention Aggregating Network for Salient Object Detection'

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

date: '2022-09-25T00:00:00Z'
doi: 'http://dx.doi.org/10.13140/RG.2.2.12217.03686'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-28T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Preprint*'
publication_short: '*Preprint*'

abstract: 'Convolutional neural networks have been introduced for salient object detection (SOD) for several years which have been proven to have the ability to achieve better performance than traditional methods. In the early stage of the development of CNN in the SOD task, most of the convolutional neural networks use simple structured feature extraction methods with fully-connected layers to generate salient masks which failed to capture and aggregate sensitive information at the different down-sample stages. The feature pyramid network (FPN) based structure with encoder and decoder is more popular for semantic segmentation and salient object detection tasks, the FPN structure with attention modules can efficiently capture the important area of input feature and achieve better performance. In this paper, to improve the overall performance of salient object detection tasks, we propose a dual attention aggregating network (DAANet), which is an FPN-based deep convolutional neural network with a dual attention aggregation module (DAAM) and boundary-joint training. The DAAM considers the salient map prediction from the low-level output as pseudo-attention which can efficiently aggregate multi-scale information. The Convolution block attention module (CBAM) in DAAM can refine the aggregation of pseudo-attention which enables better performance. We evaluate our proposed DAANet on six benchmark datasets and analyze the effectiveness of each module of DAANet which shows that DAANet outweighs other previous approaches in many aspects. In addition, the lightweight configuration of the model can achieve an MAE of 0.051 on the DUTS-TE dataset with only 15.8 MB of parameters. In the spirit of reproducible research, the model code, dataset, and results of the experiments in this paper are available at: https://github.com/Att100/DAANet.'

# Summary. An optional shortened abstract.
summary: In this paper, to improve the overall performance of salient object detection tasks, we propose a dual attention aggregating network (DAANet), which is an FPN-based deep convolutional neural network with a dual attention aggregation module (DAAM) and boundary-joint training. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/DAANet_sod_2022.pdf'
url_code: 'https://github.com/Att100/DAANet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overall Pipline of DAANet'
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
