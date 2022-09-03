---
title: A Simple Deep Learning System
summary: A Simple Deep Learning System
tags:
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Netron visualization of Caffe-format computation graph
  focal_point: Smart

links: []
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: 'https://github.com/Att100/Simple-DeepLearning-System'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---

## Introduction

This is a simple deep learning system with numpy. It include a `autograd` system which is the basis of the whole system while all network layers and tensor
operations that implemented are based on the simple dynamic computation graph. We now support fundamental mathmatics operation and several layers, including `Linear`, 
`ReLU`, `Dropout1d`, `BatchNorm1d`, `Softmax`, and some pre-defined loss functions such as `MSELoss` and `CrossEntropyLoss`. We plan to support some core components of 
convolution nerual networks and CUDA in the future. 

## Quick Start

- Run example of linear regression

  ```
  python ex_linear_regression.py
  ```

- Run example of MLP on MNIST dataset

  ```
  python ex_mlp_mnist.py
  ```