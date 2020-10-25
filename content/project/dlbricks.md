---
title: DLBricks
summary: Composable Benchmark Generation to Reduce Deep Learning Benchmarking Effort on CPUs.
tags:
  - Deep Learning
  - Benchmarking
date: '2019-10-18T00:00:00Z'
# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption:
  focal_point:

# links:
# - icon:
#   icon_pack:
#   name:
#   url:
url_code: ''
url_pdf: 'pdf/dlbricks-icpe20.pdf'
url_slides: 'pdf/dlbricks-icpe20-slides.pdf'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

The past few years have seen a surge of applying Deep Learning (DL) models for a wide array of tasks such as image classification, object detection, machine translation, etc. While DL models provide an opportunity to solve otherwise intractable tasks, their adoption relies on them being optimized to meet latency and resource requirements. Benchmarking is a key step in this process but has been hampered in part due to the lack of representative and up-to-date benchmarking suites. This is exacerbated by the fast-evolving pace of DL models.

We propose DLBricks, a composable benchmark generation design that reduces the effort of developing, maintaining, and running DL benchmarks on CPUs. DLBricks decomposes DL models into a set of unique runnable networks and constructs the original model’s performance using the performance of the generated benchmarks. DLBricks leverages two key observations: DL layers are the performance building blocks of DL models and layers are extensively repeated within and across DL models. Since benchmarks are generated automatically and the benchmarking time is minimized, DLBricks can keep up-to-date with the latest proposed models, relieving the pressure of selecting representative DL models. Moreover, DLBricks allows users to represent proprietary models within benchmark suites. We evaluate DLBricks using 50 MXNet models spanning 5 DL tasks on 4 representative CPU systems. We show that DLBricks provides an accurate performance estimate for the DL models and reduces the benchmarking time across systems (e.g. within 95% accuracy and up to 4.4× benchmarking time speedup on Amazon EC2 c5.xlarge).
