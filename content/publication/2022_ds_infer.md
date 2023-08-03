+++
title = "Deepspeed inference: Enabling efficient inference of transformer models at unprecedented scale"
date = "2022-06-30"  # Schedule page publish date.
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Reza Yazdani Aminabadi", "Samyam Rajbhandari", "Minjia Zhang", "Ammar Ahmad Awan", "admin", "Du Li", "Elton Zheng", "Jeff Rasley", "Shaden Smith", "Olatunji Ruwase", "Yuxiong He"]

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
publication = "*Super Computing*"
publication_short = "**Super Computing**"

# Abstract and optional shortened version.
abstract = """The landscape of transformer model inference is increasingly diverse in model size, model characteristics, latency and throughput requirements, hardware requirements, etc. With such diversity, designing a versatile inference system is challenging, addresses these challenges by (1) a multi-GPU inference solution to minimize latency while maximizing throughput for both dense and sparse transformers when the model fits in aggregate GPU memory, and (2) a heterogeneous inference solution that leverages CPU/NVMe/GPU memory to enable high-throughput inference for models larger than aggregate GPU memory, reduces latency by 6.4x and increases throughput by 4x over the state-of-the-art while achieving 260 TFLOPS/GPU throughput (over 80% of A100 peak). It enables trillion parameter scale inference under real-time latency constraints by leveraging hundreds of GPUs, an unprecedented scale for inference. It can inference 25x larger models than with GPU only solutions, while delivering a high throughput of 84 TFLOPS (over 50% of A6000 peak)."""


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
url_pdf = "pdf/ds-infer-sc22.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = "/project/deepspeed"
url_slides = ""
url_video = ""
url_poster = ""
url_source = "https://github.com/microsoft/DeepSpeed"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
