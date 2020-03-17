+++
title = "State Dependent Control of Closed Queueing Networks with Application to Ride-Hailing"
date = 2018-03-13

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["S. Banerjee", "Y. Kanoria", "Pengyu Qian"]

authorinfo = "with S. Banerjee and Y. Kanoria"
versioninfo = "major revision in"
journalinfo = "Operations Research"
confinfo = "ACM SIGMETRICS"
confyear = "2018"
journalno = "1"
absinfo = "Inspired by ride-hailing and bike-sharing systems, we study the design of state-dependent controls for a closed queueing network model. We focus on the assignment policy, where the platform can choose which nearby vehicle to assign to an incoming customer; if no units are available nearby, the request is dropped. The vehicle becomes available at the destination after dropping the customer. We study how to minimize the proportion of dropped requests in steady state.

We propose a family of simple state-dependent policies called Scaled MaxWeight (SMW) policies that dynamically manage the geographical distribution of supply. We prove that under the complete resource pooling (CRP) condition (analogous to the condition in Hall's marriage theorem), each SMW policy leads to exponential decay of demand-dropping probability as the number of supply units scales to infinity. Further, there is an SMW policy that achieves the \textbf{optimal} exponent among all assignment policies, and we analytically specify this policy in terms of the customer arrival rates for all source-destination pairs. The optimal SMW policy maintains high supply levels near structurally under-supplied locations. We also propose data-driven approaches for designing SMW policies and demonstrate excellent performance in simulations based on the NYC taxi dataset."

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
url_pdf = "pdf/State_Dependent_Closed_QNet_BKQ.pdf"
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
links = [{name = "Conference Version", url = "https://dl.acm.org/citation.cfm?id=3219619"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
 
+++
