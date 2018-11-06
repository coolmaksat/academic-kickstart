+++
title = "DeepGO"
date = 2018-11-05T11:50:48+03:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["gene-ontology", "deep-learning", "machine-learning", "CNN"]

# Project summary to display on homepage.
summary = "DeepGO is a novel method for predicting protein functions using protein sequences and protein-protein interaction (PPI) networks."

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = "https://github.com/bio-ontology-research-group/deepgo"
url_dataset = ""
url_project = "http://deepgo.bio2vec.net/deepgo/"
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

[header]
  image = "headers/deepgo.png"
  caption = "DeepGO"
+++
DeepGO is a novel method for predicting protein functions using
protein sequences and protein-protein interaction (PPI) networks.  It
uses deep neural networks to learn sequence features and PPI
embeddings learned with knowledge graph representation learning method
and hierarchically classifies proteins with GO classes.