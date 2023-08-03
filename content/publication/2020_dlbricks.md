+++
title = "DLBricks: Composable Benchmark Generation to Reduce Deep Learning Benchmarking Effort on CPUs"
date = "2020-01-20"

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
publication = "*International Conference on Performance Engineering*"
publication_short = "**ICPE**"

# Abstract and optional shortened version.
abstract = """The past few years have seen a surge of applying Deep Learning (DL) models for a wide array of tasks such as image classification, object detection, machine translation, etc. While DL models provide an opportunity to solve otherwise intractable tasks, their adoption relies on them being optimized to meet latency and resource requirements. Benchmarking is a key step in this process but has been hampered in part due to the lack of representative and up-to-date benchmarking suites. This is exacerbated by the fast-evolving pace of DL models.

This paper proposes DLBricks, a composable benchmark generation design that reduces the effort of developing, maintaining, and running DL benchmarks on CPUs. DLBricks decomposes DL models into a set of unique runnable networks and constructs the original model's performance using the performance of the generated benchmarks. DLBricks leverages two key observations: DL layers are the performance building blocks of DL models and layers are extensively repeated within and across DL models. Since benchmarks are generated automatically and the benchmarking time is minimized, DLBricks can keep up-to-date with the latest proposed models, relieving the pressure of selecting representative DL models. Moreover, DLBricks allows users to represent proprietary models within benchmark suites. We evaluate DLBricks using 50 MXNet models spanning 5 DL tasks on 4 representative CPU systems. We show that DLBricks provides an accurate performance estimate for the DL models and reduces the benchmarking time across systems (e.g. within 95% accuracy and up to 4.4× benchmarking time speedup on Amazon EC2 c5.xlarge)."""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "pdf/dlbricks-icpe20.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = "/project/dlbricks"
url_slides = "pdf/dlbricks-icpe20-slides.pdf"
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
