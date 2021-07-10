---
draft: false

title: "Combining topic modeling and regression: Supervised topic modeling with covariates"
event: 85th Annual Meeting of the Psychometric Society
event_url: https://www.psychometricsociety.org/speakers-0

location: University of Maryland
address:
  street:
  city: College Park
  region: MD
  postcode:
  country: United States

abstract: "As text data become larger and increasingly accessible in psychological research, the need for appropriate statistical models has grown. One statistical framework, topic modeling, models patterns of word co-occurrences using discrete latent topics. Unsupervised topic models such as Latent Dirichlet Allocation (Blei, Ng, & Jordan, 2003) are typically used to estimate topic proportions as a summary of the text (e.g., to understand the content of survey responses). In psychology, it is common to use these estimated topic proportions as regression predictors in a two-stage approach. However, it is well-known (e.g., in the factor analysis literature) that such a two-stage procedure can be problematic. We propose a novel extension of the supervised topic model (Blei & McAuliffe, 2008) that jointly estimates a topic model and a regression model that incorporates both the latent topics and other covariates as predictors. Our model, Supervised Latent Dirichlet Allocation with Covariates (SLDAX), can be fit in a single stage rather than two stages, allows for evaluation of the incremental validity of the topics given other established measures (and vice versa), and models relationships between the topics and the outcome. To estimate the SLDAX model, we derived a Gibbs sampling algorithm and developed an accompanying R package, psychtm, that implements SLDAX. Performance of the model for different data characteristics was evaluated in a simulation study. We demonstrate the application of SLDAX on an empirical data set."
summary: "Spotlight Talk"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-07-13"
date_end: "2020-07-17"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2020-03-16T00:00:00Z"

authors:
- admin
- Ross Jacobucci
- Zhiyong Zhang

tags:
- SLDAX
- topic modeling
- Bayesian
- text mining

# Is this a featured talk? (true/false)
featured: true

# Optional header image (relative to `assets/media/` folder)
# header:
#   caption:
#   image: "sldax-dag.png"

# image:
#   caption: 'Directed acylic graphical representation of an SLDAX model with a Gaussian outcome.'
# focal_point: Smart  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: "./slides/2020imps-sldax-slides.pdf"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- topic-model

# Enable math on this page?
math: false
---

{{< figure library="true" src="sldax-dag.png" title="Directed acyclic graph of the SLDAX model." >}}
