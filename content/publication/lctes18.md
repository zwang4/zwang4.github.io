+++
title = "Adaptive Deep Learning Model Selection on Embedded Systems "
date = 2018-03-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Taylor, B.", "Sanz Marco, V.", "Wolff, W.", "Elkhatib, Y.",  "**Wang, Z**" ]

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
publication = "In The 19th Annual ACM SIGPLAN/SIGBED Conference on Languages, Compilers, and Tools for Embedded Systems (**LCTES**) (~~Artificate Evaluated!~~)"
publication_short = "LCTES '18"
publication_url = "https://conf.researchr.org/track/LCTES-2018/LCTES-2018-papers"

# Abstract and optional shortened version.
abstract = "The recent ground-breaking advances in deep learnin gnetworks (DNNs) make them attractive for embedded systems. However, it can take a long time for DNNs to make an inference on resource-limited embedded devices. Offloading the computation into the cloud is often infeasible due to privacy concerns, high latency, or the lack of connectivity. As such, there is a critical need to find a way to effectively execute the DNN models locally on the devices. This paper presents an adaptive scheme to determine which DNN model to use for a given input, by considering the desired accuracy and inference time. Our approach employs machine learning to develop a predictive model to quickly select a pre-trained DNN to use for a given input and the optimization constraint. We achieve this by first training off-line a predictive model, and then use the learnt model to select a DNN model to use for new, unseen inputs. We apply our approach to the image classification task and evaluate it on a Jetson TX2 embedded deep learning platform using the ImageNet ILSVRC 2012 validation dataset. We consider a range of influential DNN models. Experimental results show that our approach achieves a 7.52% improvement in inference accuracy, and a 1.8x reduction in inference time over the most-capable single DNN model."


abstract_short = "Optimising comptuational intensive deep learning models on embedded devices"

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
url_pdf = "publications/lctes18.pdf"
#url_preprint = "#"
url_code = "https://zenodo.org/record/1242583#.Ww7a0qinHAR"
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

