+++
title = "Data-driven Simulation of a Thermal Comfort-based Temperature Set-point Control with ASHRAE RP884"
date = 2019-03-06T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["S. Lu", "W Wang", "C. Lin", "E. Hameen"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Building and Environment*"
publication_short = "*Building and Environment*"

# Abstract and optional shortened version.
abstract = "In the course of thermal comfort theory, researchers have been investigating both static thermal comfort and adaptive thermal comfort. Compared to static thermal comfort metrics such as predicted mean vote (PMV), adaptive thermal comfort emphasizes the interactions between occupants and indoor environment by collecting both environment-related and occupant-related data in real commercial buildings. Therefore, data-driven approaches to developing adaptive thermal comfort models have been well investigated and development of ASHRAE RP884 dataset can be seen as one of the milestones. Moreover, as thermal comfort is an occupant-centric concept for operation of HVAC system, well-developed thermal comfort model can be applied into HVAC control. Nowadays, reinforcement learning-based HVAC control has drawn much more attention in that the control system can learn by itself through the interactions between occupants and environment, which also aligns the concept of adaptive thermal comfort. Therefore, this paper mainly has two goals. The first is to develop a thermal comfort model with RP 884 of three major climate zones based on k-nearest neighbor (KNN), random forest (RF) and support vector machine (SVM). The second goal is to simulate a tabular Q-learning temperature set-point control system with the statistical thermal comfort model. The results have shown that the best recall of the statistical thermal comfort model is 49.3%, which outperforms that of PMV being 43% based on 7-point thermal sensation scale. In addition, the Q-learning based temperature control can indeed reach the comfortable temperature ranges for occupants with whatever initial temperature set-point."

#Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
# projects = ["example-external-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://www.sciencedirect.com/science/article/pii/S0360132319301647"

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
