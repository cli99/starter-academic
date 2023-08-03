+++
title = "Benanza: Automatic μBenchmark Generation to Compute ''Lower-bound'' Latency and Inform Optimizations of Deep Learning Models on GPUs"
date = "2020-01-26"
featured = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin", "Abdul Dakkak", "Jinjun Xiong", "Wen-mei Hwu"]

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
publication = "*International Parallel and Distributed Processing Symposium*"
publication_short = "**IPDPS**"

# Abstract and optional shortened version.
abstract = """As Deep Learning (DL) models have been increasingly used in latency-sensitive applications, there has been a growing interest in improving their response time. An important venue for such improvement is to profile the execution of these models and characterize their performance to identify possible optimization opportunities. However, the current profiling tools lack the highly desired abilities to characterize ideal performance, identify sources of inefficiency, and quantify the benefits of potential optimizations. Such deficiencies have led to slow characterization/optimization cycles that cannot keep up with the fast pace at which new DL models are introduced.

We propose Benanza, a sustainable and extensible benchmarking and analysis design that speeds up the characterization/optimization cycle of DL models on GPUs. Benanza consists of four major components: a model processor that parses models into an internal representation, a configurable benchmark generator that automatically generates micro-benchmarks given a set of models, a database of benchmark results, and an analyzer that computes the "lower-bound" latency of DL models using the benchmark data and informs optimizations of model execution. The "lower-bound" latency metric estimates the ideal model execution on a GPU system and serves as the basis for identifying optimization opportunities in frameworks or system libraries. We used Benanza to evaluate 30 ONNX models in MXNet, ONNX Runtime, and PyTorch on 7 GPUs ranging from Kepler to the latest Turing, and identified optimizations in parallel layer execution, cuDNN convolution algorithm selection, framework inefficiency, layer fusion, and using Tensor Cores."""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "pdf/benanza-ipdps20.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = "/project/benanza"
url_slides = "pdf/benanza-ipdps20-slides.pdf"
url_video = ""
url_poster = ""
url_source = "https://benanza.mlmodelscope.org/"

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
