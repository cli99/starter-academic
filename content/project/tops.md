---
title: 'TOPS'
summary: Leveraging NVIDIA’s Tensor Cores to express Collectives with matrix multiplication and exploring the benefits in terms of program simplicity, efficiency, and performance.
tags:
  - GPU
  - Algorithms
date: '2019-01-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption:
  focal_point:

links:
- icon: github
  icon_pack: fab
  name: tcu_scope
  url: 'https://github.com/c3sr/tcu_scope'
url_code: 
url_pdf: 'pdf/tops-ics.pdf'
url_slides: 'https://tcu.c3sr.com/'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

Driven by deep learning, there has been a surge of specialized processors for matrix multiplication, referred to as Tensor Core Units (TCUs). These TCUs are capable of performing matrix multiplications on small matrices (usually 4 × 4 or 16 × 16) to accelerate HPC and deep learning workloads. Although TCUs are prevalent and promise increase in performance and/or energy efficiency, they suffer from over specialization as only matrix multiplication on small matrices is supported. In this paper we express both reduction and scan in terms of matrix multiplication operations and map them onto TCUs. To our knowledge, this paper is the first to try to broaden the class of algorithms expressible as TCU operations and is the first to show benefits of this mapping in terms of: program simplicity, efficiency, and performance. We implemented the reduction and scan algorithms using NVIDIA’s V100 TCUs and achieved 89% − 98% of peak memory copy bandwidth. Our results are orders of magnitude faster (up to 100x for reduction and 3x for scan) than state-of-the-art methods for small segment sizes (common in HPC and deep learning applications). Our implementation achieves this speedup while decreasing the power consumption by up to 22% for reduction and 16% for scan.
