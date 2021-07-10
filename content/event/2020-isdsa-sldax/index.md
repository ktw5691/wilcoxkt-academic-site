---
title: "Modeling relationships from themes in text and covariates with an outcome: A Bayesian supervised topic model with covariates"
event: 2nd Annual Meeting of the International Society for Data Science and Analytics
event_url: https://meeting.isdsa.org/index.php/isdsa/2020

location: University of Notre Dame
address:
  street:
  city: Notre Dame
region: IN
postcode:
  country: United States

summary:
abstract: "While text analysis has long been of interest in psychology, quantitative approaches tend to rely on predefined dictionaries of words designed to correspond to constructs of interest. However, construction of dictionaries can be time-consuming and dictionary-based methods cannot accommodate relevant words that fall outside the dictionary. Furthermore, dictionary methods typically assign a word to only one construct and fail to account for polysemy and homonymy. One alternative approach, topic modeling, eschews predefined dictionaries and instead models patterns of word co-occurrences using latent categories (i.e., topics). These topics have multiple uses and are often incorporated as components of a subsequent model. In psychological research, unsupervised topic models are typically used to obtain estimated topic proportions as a summary of the text (e.g., to understand the content of survey responses). Associations between these estimated topic proportions and an outcome of interest may be modeled (e.g., in a regression model) as a second stage. However, it is well-known (e.g., in the factor analysis literature) that a two-stage procedure that uses estimated latent variables can be problematic. We propose an extension of the supervised topic model (Blei & McAuliffe, 2008) that jointly estimates a topic model and a regression model to predict an outcome using both the latent topic proportions and other manifest predictors. Our model, supervised latent Dirichlet allocation with covariates (SLDAX), can be fit in a single stage rather than two stages, allows for evaluation of the incremental validity of the topics given other established measures (or vice versa), provides concise summarization of the text, and models relationships between the topics and the outcome. To estimate the SLDAX model, we derived a Markov Chain Monte Carlo sampling algorithm. We also developed an R package, psychtm, that implements SLDAX. Performance of the model for different data characteristics (e.g., number of documents, document lengths, number of topics, presence of covariates) is evaluated in a simulation study. These results are used to make recommendations regarding suggested data requirements for the use of the SLDAX model in applications. Finally, we demonstrate the application of SLDAX on an empirical data set."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-05-26T00:00:00
date_end: 2020-05-27T00:00:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2020-02-05T00:00:00"

authors:
- admin
- Ross Jacobucci
- Zhiyong Zhang

tags:
- SLDAX
- topic model
- text mining
- Bayesian

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
url_slides: "./slides/2020isdsa-sldax-slides.pdf"
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides: ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- topic-model

math: false
---

{{< figure library="true" src="sldax-dag.png" title="Directed acyclic graph of the SLDAX model." >}}
