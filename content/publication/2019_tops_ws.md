+++
title = "Accelerating Reduction Using Tensor Core Units"
date = "2019-02-16"  # Schedule page publish date.
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Abdul Dakkak", "Cheng Li", "Jinjun Xiong", "Isaac Gelado", "Wen-Mei Hwu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*Intersection of High Performance Computing and Machine Learning 2019*"
publication_short = "**HPCaML**"

# Abstract and optional shortened version.
abstract = """Driven by deep learning, there has been a surge of specialized processors for matrix multiplication, referred to as Tensor Core Units (TCUs). These TCUs come under the guise of different marketing terms and are capable of performing matrix multiplications on small matrices (usually 4x4 or 16x16) to accelerate the convolutional and recurrent neural networks in deep learning workloads. Although TCUs are prevalent and promise an increase in performance and/or energy efficiency, they suffer from over-specialization — with only general matrix-matrix multiplication (GEMM) being supported. This limits their applicability to general algorithms and makes them confined to narrowly specialized libraries and application domains. In this work, we leverage NVIDIA's TCU to express reduction in terms of matrix multiplication and show the benefits — in terms of program simplicity, efficiency, and performance compared to start-of-the-art reduction methods on the GPU. Although this work targets GPUs, the motivation, methods, and observations apply to a wide number of TCU implementations and microarchitectures."""
abstract_short = "In this paper we express reduction in terms of matrix multiplication operations and map them onto Tensor Core Units."


# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#   projects = [""]

# Links (optional)
url_pdf = "pdf/tops-hpcaml19"
url_preprint = ""
url_code = "https://github.com/c3sr/tcu_scope"
url_dataset = ""
url_project = "/project/tops"
url_slides = "https://hpc.pnl.gov/hpcaml19/"
url_video = ""
url_poster = ""
url_source = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
