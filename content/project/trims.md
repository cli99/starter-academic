---
title: 'TrIMS'
summary: Transparent and Isolated Model Sharing for Low Latency Deep Learning Inference in Function as a Service Environments.
tags:
  - Deep Learning
  - GPU
  - Cloud
date: '2019-02-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption:
  focal_point:

links:
- icon: github
  icon_pack: fab
  name: trims-mxnet
  url: 'https://github.com/rai-project/trims_mxnet'
url_code: 
url_pdf: 'pdf/trims-cloud19.pdf'
url_slides: 'pdf/trims-cloud19-slides.pdf'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

Deep neural networks (DNNs) have become core computation components within low latency Function as a Service (FaaS) prediction pipelines. Cloud computing, as the de-facto backbone of modern computing infrastructure, has to be able to handle user-defined FaaS pipelines containing diverse DNN inference workloads while maintaining isolation and latency guarantees with minimal resource waste. The current solution for guaranteeing isolation and latency within FaaS is inefficient. A major cause of the inefficiency is the need to move large amount of data within and across servers. We propose TrIMS as a novel solution to address this issue. TrIMS is a generic memory sharing technique that enables constant data to be shared across processes or containers while still maintaining isolation between users. TrIMS consists of a persistent model store across the GPU, CPU, local storage, and cloud storage hierarchy, an efficient resource management layer that provides isolation, and a succinct set of abstracts, application APIs, and container technologies for easy and transparent integration with FaaS, Deep Learning (DL) frameworks, and user code. We demonstrate our solution by interfacing TrIMS with the Apache MXNet framework and demonstrate up to 24× speedup in latency for image classification models, up to 210× speedup for large models, and up to 8× system throughput improvement.
