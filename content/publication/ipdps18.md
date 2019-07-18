+++
title = "Auto-tuning Streamed Applications on Intel Xeon Phi "
date = 2018-01-07T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Zhang, P.", "Fang, J.", "Tang, T.", "Yang, C.", "**Wang, Z**"]

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
publication = "In 32nd IEEE International Parallel & Distributed Processing Symposium (**IPDPS**)"
publication_short = "IPDPS '18"
publication_url = "http://ipdps.org/"

# Abstract and optional shortened version.
abstract="Many-core accelerators, as represented by the XeonPhi coprocessors and GPGPUs, allow software to exploit spatial and temporal sharing of computing resources to improve the overall system performance. To unlock this performance potential requires software to effectively partition the hardware resource to maximize the overlap between hostdevice communication and accelerator computation, and to match the granularity of task parallelism to the resource partition. However, determining the right resource partition and task parallelism on a per program, per dataset basis is challenging. This is because the number of possible solutions is huge, and the benefit of choosing the right solution may be large, but mistakes can seriously hurt the performance. In this paper, we present an automatic approach to determine the hardware resource partition and the task granularity for any given application, targeting the Intel XeonPhi architecture. Instead of hand-crafting the heuristic for which the process will have to repeat for each hardware generation, we employ machine learning techniques to automatically learn it. We achieve this by first learning a predictive model offline using training programs; we then use the learned model to predict the resource partition and task granularity for any unseen programs at runtime. We apply our approach to 23 representative parallel applications and evaluate it on a CPU-XeonPhi mixed heterogenous many-core platform. Our approach achieves, on average, a 1.6x (upto 5.6x) speedup, which translates to 94.5% of the performance delivered by a theoretically perfect predictor."


abstract_short = "Auto-tuning streamed programs on Intel XeonPhi"

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
#url_pdf = "publications/ipdps18.pdf"
url_preprint = "publications/ipdps18.pdf"
#url_preprint = "#"
url_code = "https://github.com/Wisdom-moon/hStreams-benchmark"
#url_dataset = "https://zenodo.org/record/1242583#.Ww7a0qinHAR"
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

