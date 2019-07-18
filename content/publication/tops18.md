+++
title = "A Video-based Attack for Android Pattern Lock"
date = 2018-06-28T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Guixin Ye", "Zhanyong Tang", "Dingyi Fang", "Xiaojiang Chen", "Willy Wolff", "Adam Aviv", "**Zheng Wang**" ]

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
publication = "ACM Transactions on Privacy and Security (**ACM TOPS**)"
publication_short = "ACM TOPS"

# Abstract and optional shortened version.
abstract="Pattern lock is widely used for identification and authentication on Android devices. This article presents a novel video-based side channel attack that can reconstruct Android locking patterns from video footage filmed using a smartphone. As a departure from previous attacks on pattern lock, this new attack does not require the camera to capture any content displayed on the screen. Instead, it employs a computer vision algorithm to track the fingertip movement trajectory to infer the pattern. Using the geometry information extracted from the tracked fingertip motions, the method can accurately infer a small number of (often one) candidate patterns to be tested by an attacker. We conduct extensive experiments to evaluate our approach using 120 unique patterns collected from 215 independent users. Experimental results show that the proposed attack  can reconstruct over 95% of the patterns in five attempts. We discovered that, in contrast to most people's belief, complex patterns do not offer stronger protection under our attacking scenarios. This is demonstrated by the fact that we are able to break all but one complex patterns (with a 97.5% success rate) as opposed to 60% of the simple patterns in the first attempt. We demonstrate that this video-side channel is a serious concern for not only graphical locking patterns but also PIN-based passwords, as algorithms and analysis developed from the attack can be easily adapted to target PIN-based passwords. As a countermeasure, we propose to change the way the Android locking pattern is constructed and used. We show that our proposal can successfully defeat this video-based attack. We hope the results of this article can encourage the community to revisit the design and practical use of Android pattern lock."


abstract_short = "A new video-based attack on Android pattern lock"

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
url_preprint = "publications/tops18.pdf"
publication_url="https://tops.acm.org/"
#url_preprint = "#"
#url_code = "https://github.com/Wisdom-moon/hStreams-benchmark"
url_dataset = "https://dx.doi.org/10.17635/lancaster/researchdata/113"
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

