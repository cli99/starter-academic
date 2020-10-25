---
title: KLAP
summary: Kernel Lauch Aggregation and Promotion (KLAP), a set of compiler techniques that improve the performance of GPU kernels which use dynamic parallelism.
tags:
  - GPU
  - Compiler
date: '2016-08-30T00:00:00Z'
draft: false

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption:
  focal_point:

links:
  - icon: github
    icon_pack: fab
    name: klap
    url: https://github.com/illinois-impact/klap
url_code: ''
url_pdf: 'pdf/klap-micro2016.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

Dynamic parallelism on GPUs simplifies the programming of many classes of applications that generate paral-lelizable work not known prior to execution. However, modern GPUs architectures do not support dynamic parallelism efficiently due to the high kernel launch overhead, limited number of simultaneous kernels, and limited depth of dynamic calls a device can support.

We proposed Kernel Lauch Aggregation and Promotion (KLAP), a set of compiler techniques that improve the performance of kernels which use dynamic parallelism. More details are in the [paper](/publication/klap/).
