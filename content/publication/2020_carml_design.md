+++
title = "The Design and Implementation of a Scalable DL Benchmarking Platform (Best Paper Award)"
date = "2020-04-21"  # Schedule page publish date.
draft = false
featured = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin", "Abdul Dakkak", "Jinjun Xiong", "Wen-mei Hwu"]
author_notes = ['Equal contribution', 'Equal contribution']

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*IEEE CLOUD*"
publication_short = "**IEEE CLOUD**"

# Abstract and optional shortened version.
abstract = """The current Deep Learning (DL) landscape is fast-paced and is rife with non-uniform models, hardware/software (HW/SW) stacks, but lacks a DL benchmarking platform to facilitate evaluation and comparison of DL innovations, be it models, frameworks, libraries, or hardware. Due to the lack of a benchmarking platform, the current practice of evaluating the benefits of proposed DL innovations is both arduous and error-prone - stifling the adoption of the innovations.

In this work, we first identify 10 design features which are desirable within a DL benchmarking platform. These features include: performing the evaluation in a consistent, reproducible, and scalable manner, being framework and hardware agnostic, supporting real-world benchmarking workloads, providing in-depth model execution inspection across the HW/SW stack levels, etc. We then propose MLModelScope, a DL benchmarking platform design that realizes the 10 objectives. MLModelScope proposes a specification to define DL model evaluations and techniques to provision the evaluation workflow using the user-specified HW/SW stack. MLModelScope defines abstractions for frameworks and supports a broad range of DL models and evaluation scenarios. We implement MLModelScope as an open-source project with support for all major frameworks and hardware architectures. Through MLModelScope's evaluation and automated analysis workflows, we performed case-study analyses of 37 models across 4 systems and show how model, hardware, and framework selection affects model accuracy and performance under different benchmarking scenarios. We further demonstrated how MLModelScope's tracing capability gives a holistic view of model execution and helps pinpoint bottlenecks."""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "pdf/carml-cloud20.pdf"
url_preprint = ""
url_code = "https://github.com/rai-project/mlmodelscope"
url_dataset = ""
url_project = "/project/mlmodelscope"
url_slides = "pdf/carml-cloud20-slides.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
