+++
title = "CrossSense: Towards Cross-Site and Large-Scale WiFi Sensing "
date = 2018-07-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jie Zhang", "Zhanyong Tang", "Meng Li", "Dingyi Fang", "Petteri Nurmi", "**Zheng Wang**"]

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
publication = "In The 24th ACM International Conference on Mobile Computing and Networking (**MobiCom**)"
publication_short = "MobiCom '18"
publication_url = "https://sigmobile.org/mobicom/2018/"


# Abstract and optional shortened version.
abstract = "WiFi has recently established itself as a powerful medium for sensing. By measuring how the wireless channel is affected by humans and activities and then correlating the measurement to pre-collected WiFi training samples, rich information ranging from gestures to gait patterns and even vital signs can be identified. However, WiFi sensing solutions currently have limited scale as they require training data to be meticulously collected in each deployment environment and as they are designed for small sets of activities. This paper presents CrossSense, a novel system for scaling up WiFi sensing to new environments and larger problems. To reduce the cost of sensing model training data collection, CrossSense employs machine learning to train, off-line, a roaming model to generate, from one set of measurements, synthetic training samples for each target environment. To scale up to a larger problem size, CrossSense adopts a mixture-of-experts approach where multiple specialized sensing models, or experts, are used to capture the mapping from diverse WiFi inputs to the desired output. The experts are trained offline and at runtime the appropriate expert for a given input is automatically chosen. We evaluate CrossSense by applying it to two representative WiFi sensing applications, gait identification and gesture recognition. We show that CrossSense boosts the accuracy of state-of-the-art WiFi sensing techniques from 20% to over 80% and 90% for gait identification and gesture recognition respectively, delivering consistently good performance -- particularly when the problem size is significantly greater than that current approaches can effectively handle."


abstract_short = "Enable Cross-site Wireless Sensing at a Larger Scale"

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
url_preprint = "publications/mobicom18.pdf"
#url_pdf = "http://www.lancaster.ac.uk/staff/wangz3/publications/mobicom'18.pdf"
#url_preprint = "#"
url_code = "https://goo.gl/4z4iXv"
url_dataset = "https://goo.gl/4z4iXv"
#url_project = "#"
#url_slides = "http://homepages.inf.ed.ac.uk/s0786582/publications/Zheng_PPoPP2009.pdf"
url_video = "https://youtu.be/wfof_I5jqDo"
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

