+++
title = "Dynamic Assignment Control of a Closed Queueing Network under Complete Resource Pooling"
date = 2018-03-13

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["S. Banerjee", "Y. Kanoria", "Pengyu Qian"]

authorinfo = "with S. Banerjee and Y. Kanoria"
versioninfo = "major revision in"
journalinfo = "Operations Research"
confinfo = "ACM SIGMETRICS"
confyear = "2018"
journalno = "1"
absinfo = "We study the design of dynamic assignment control in networks with a fixed number of circulating resources (supply units). Each time a demand arises, the controller has (limited) flexibility in choosing the node from which to assign a supply unit. If no supply units are available at any compatible node, the demand is lost. If the demand is served, this causes to the supply unit to relocate to the 'destination' of the demand. We study how to minimize the proportion of lost requests in steady state (or over a finite horizon) via a large deviations analysis. 

We propose a family of simple state-dependent policies called Scaled MaxWeight (SMW) policies that dynamically manage the distribution of supply in the network. We prove that under a complete resource pooling condition (analogous to the condition in Hall's marriage theorem), any SMW policy leads to exponential decay of demand-loss probability as the number of supply units scales to infinity. Further, there is an SMW policy that achieves the optimal loss exponent among all assignment policies, and we analytically specify this policy in terms of the demand arrival rates for all origin-destination pairs. The optimal SMW policy maintains high supply levels adjacent to structurally under-supplied nodes. We discuss two applications: (i) Shared transportation platforms (like ride-hailing and bikesharing): We incorporate travel delays in our model and show that SMW policies for assignment control continue to have exponentially small loss. Simulations of ride-hailing based on the NYC taxi dataset demonstrate excellent performance. (ii) Service provider selection in scrip systems (like for babysitting or for kidney exchange): With only cosmetic modifications to the setup, our results translate fully to a model of scrip systems and lead to strong performance guarantees for a 'Scaled Minimum Scrip' service provider selection rule."

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
