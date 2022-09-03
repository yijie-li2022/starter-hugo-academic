---
title: PaddlePaddle Reproduction of DDPM
summary: PaddlePaddle Reproduction of paper Denoising Diffusion Probabilistic Models
tags:
  - Reproduction
  - Deep Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: CelebA-HQ (128x128) generated samples
  focal_point: Smart

links: []
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: 'https://github.com/Att100/PaddlePaddle-DDPM'
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

This is a PaddlePaddle reproduction of Denoising Diffusion Probabilistic Models (DDPM) and Denoising Diffusion Implicit Models (DDIM). We trained the diffusion model with original-designed UNet on CIFAR10 (32X32) and simplified verison (FPN, according to [Keras-DDPM](https://github.com/bojone/Keras-DDPM)) on CelebA-HQ (128X128). 

<div style='color: red'>Warning: We don't recommend you to use the CIFAR10 training script of this repo, because it may have some bugs which may lead to a low FID, and we will try to fix this problem in the future.</div>

## Quick Start

- Download pretrained weights and place in folder `ckpt`

  [Baidu Yun](https://pan.baidu.com/s/1VV7IH0mXzIwtCFXlCers7w?pwd=tew7), password: `tew7`

- Use pretrained weights to do the generation (DDPM)

  ```
  python run_cifar10.py --pretrained_path './ckpts/ddpm_cifar10_i800000_ema.pdparam' --num_images '400-20-20' --mode 'denoise'
  ```

- Use pretrained weights to do the generation (DDIM)

  ```
  python run_celeba_hq_ddim.py --pretrained_path './ckpts/ddpm_cifar10_i1000000_ema.pdparam' --num_images '64-8-8' --batchsize 64
  ```