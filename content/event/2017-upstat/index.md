---
title: Text mining with a Bayesian hidden topic Markov model
event: Sixth Annual Joint Conference of the Upstate Chapters of the American Statistical Association
event_url: https://www.rochester.edu/up-stat/index.html
location: ""
address:
  street: ""
  city: Buffalo
  region: NY
  postcode:
  country: United States

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2017-04-21
date_end: 2017-04-23
all_day: true

publishDate: "2017-04-01T00:00:00"
draft: false

authors:
- admin

# Abstract and optional shortened version.
abstract: "Topic models are a state-of-the-art probabilistic approach to extracting structural information about discrete data and have been used with great success for text mining. A recent development in topic modeling, the Hidden Topic Markov Model (HTMM), incorporates hidden Markov models, resulting in contiguous topic assignments and word sense disambiguation. This is a departure from the standard 'bag-of-words' assumption of the seminal Latent Dirichlet Allocation (LDA). While LDA can handle word synonymy, it restricts each word to belong to a single topic. HTMM is capable of assigning a given word to multiple topics depending on location within a document. An expectation-maximization (EM) algorithm for inference was proposed by Gruber, Rosen-Zvi, and Weiss (2007) that takes advantage of existing EM techniques for hidden Markov models, but a full derivation was never published. I derive the special state space used by HTMM and approach inference for HTMM in two ways: First, a full derivation of an EM algorithm for frequentist inference and second, a novel Gibbs sampler for Bayesian inference."
summary: ""

featured: false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects: []`.
projects:
- topic-model

tags:
- topic model
- Bayesian
- text mining

url_pdf:
url_slides:
url_video:
url_code:

math: false

# Optional header image (relative to `assets/media/` folder)
# header:
#   caption:
#   image: "htmm-dag.png"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: "Graphical model of the Hidden Topic Markov Model."
#   focal_point: "Smart" # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
---

{{< figure library="true" src="htmm-dag.png" title="Graphical model of the Hidden Topic Markov Model." >}}
