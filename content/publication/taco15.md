+++
title = "Automatic and Portable Mapping of Data Parallel Programs to OpenCL for GPU-based Heterogeneous Systems"
date = 2015-03-28T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Zheng Wang**", "Dominik Grewe", "Michael O'Boyle"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "ACM Transaction on Architecture and Code Optimization (**ACM TACO**)"
publication_short = "ACM TACO"
publication_url = "https://dl.acm.org/citation.cfm?id=2677036"

# Abstract and optional shortened version.
abstract="General purpose GPU based systems are highly attractive as they give potentially massive performance at little cost. Realizing such potential is challenging due to the complexity of programming. This article presents a compiler based approach to automatically generate optimized OpenCL code from data-parallel OpenMP programs for GPUs. A key feature of our scheme is that it leverages existing transformations, especially data transformations, to improve performance on GPU architectures and uses automatic machine learning to build a predictive model to determine if it is worthwhile running the OpenCL code on the GPU or OpenMP code on the multi-core host. We applied our approach to the entire NAS parallel benchmark suite and evaluated it on distinct GPU based systems. We achieved average (up to) speedups of 4.51x and 4.20x (143x and 67x) on a Core i7/NVIDIA GeForce GTX580 and a Core i7/AMD Radeon 7970 platforms, respectively over a sequential baseline. Our approach achieves, on average, over 10x speedups over two state-of-the-art automatic GPU code generators."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true 

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project in `content/project/`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = "publications/zheng_taco_2015.pdf"
#url_preprint = "publications/tops18.pdf"
#url_preprint = "#"
url_code = "https://github.com/zwang4/omp2ocl"
#url_dataset = "https://dx.doi.org/10.17635/lancaster/researchdata/113"
#url_project = "#"
#url_slides = "http://homepages.inf.ed.ac.uk/s0786582/publications/Zheng_PPoPP2009.pdf"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

