+++
title = "ALEA: A Fine-grained Energy Profiling Tool"
date = 2017-03-28T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Lev Mukhanov", "Pavlos Petoumenos", "**Zheng Wang**", "Nikos Parasyris", "Dimitrios S. Nikolopoulos", "Bronis R. de Supinski", "Hugh Leather"]

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
publication_url = "http://dl.acm.org/citation.cfm?id=3050436"

# Abstract and optional shortened version.
abstract="Energy efficiency is becoming increasingly important, yet few developers understand how source code changes affect the energy and power consumption of their programs. To enable them to achieve energy savings, we must associate energy consumption with software structures, especially at the fine-grained level of functions and loops. Most research in the field relies on direct power/energy measurements taken from on-board sensors or performance counters. However, this coarse granularity does not directly provide the needed fine-grained measurements. This article presents ALEA, a novel fine-grained energy profiling tool based on probabilistic analysis for fine-grained energy accounting. ALEA overcomes the limitations of coarse-grained power-sensing instruments to associate energy information effectively with source code at a fine-grained level. We demonstrate and validate that ALEA can perform accurate energy profiling at various granularity levels on two different architectures: Intel Sandy Bridge and ARM big.LITTLE. ALEA achieves a worst-case error of only 2% for coarse-grained code structures and 6% for fine-grained ones, with less than 1% runtime overhead. Our use cases demonstrate that ALEA supports energy optimizations, with energy savings of up to 2.87 times for a latency-critical option pricing workload under a given power budget. " 


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
url_pdf = "publications/aleataco.pdf"
#url_preprint = "publications/tops18.pdf"
#url_preprint = "#"
#url_code = "https://github.com/Wisdom-moon/hStreams-benchmark"
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

