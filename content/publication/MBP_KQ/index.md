+++
title = "Blind Dynamic Resource Allocation in Closed Networks via Mirror Backpressure"
date = 2019-03-07

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Y. Kanoria", "Pengyu Qian"]

authorinfo = "with Y. Kanoria"
versioninfo = "submitted."
confinfo = "ACM Conference on Economics and Computation"
confyearinfo = "EC 2020"
journalno = "2"
absinfo = "We study the problem of maximizing payoff generated over a period of time in a general class of closed queueing networks with a finite, fixed number of supply units which circulate in the system. Demand arrives stochastically, and serving a demand unit (customer) causes a supply unit to relocate from the 'origin' to the 'destination' of the customer. The key challenge is to manage the distribution of supply in the network. We consider general controls including customer entry control, pricing, and assignment. Motivating applications include shared transportation platforms and scrip systems. Inspired by the mirror descent algorithm for optimization and the backpressure policy for network control, we introduce a novel and rich family of $\\textit{Mirror Backpressure}$ (MBP) control policies. The MBP policies are simple and practical, and crucially do not need any statistical knowledge of the demand (customer) arrival rates (these rates are permitted to vary slowly in time). Under mild conditions, we propose MBP policies that are provably near optimal. Specifically, our policies lose at most $O(\\frac{K}{T}+\\frac{1}{K} + \\sqrt{\\eta K})$ payoff per customer relative to the optimal policy that knows the demand arrival rates, where $K$ is the number of supply units, $T$ is the total number of customers over the time horizon, and $\\eta$ is the maximum change in demand arrival rates per period (i.e., per customer arrival). A natural model of a scrip system is a special case of our setup. An adaptation of MBP is found to perform well in a realistic ride-hailing environment."

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract.
abstract = ""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "pdf/MBP_KQ_2020.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]
links = [{name = "Conference Version", url = "https://dl.acm.org/doi/10.1145/3391403.3399498"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
