---
title: A Bayesian hidden topic Markov model for latent linguistic structure
event: 83rd Annual Meeting of the Psychometric Society
event_url: https://www.psychometricsociety.org/content/imps-2018
location: Columbia University
address:
  street:
  city: New York
  region: NY
  postcode:
  coutry: United States

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2018-07-09
date_end: 2018-07-13
all_day: true

publishDate: "2018-07-01T00:00:00"
draft: false

authors:
- admin

# Abstract and optional shortened version.
abstract: "Topic models are a probabilistic approach to extracting structural information from discrete data and have been used with great success for text mining. The topic model is a mixture model that represents a collection of words (i.e., a document) as a mixture of topic-specific distributions over the words. A recent development in topic modeling, the Hidden Topic Markov Model (HTMM), incorporates hidden Markov models to model contiguous latent topics and better handle word sense disambiguation. This is a departure from the standard 'bag-of-words' assumption of the seminal Latent Dirichlet Allocation (LDA) model and has been shown to have better predictive accuracy for new documents and qualitatively more interpretable topics. We detail the state space model used by the HTMM and propose a Gibbs sampling algorithm for Bayesian inference. The performance of the Gibbs sampler and an EM algorithm are compared in a simulation study. The HTMM is demonstrated on an empirical data set and compared to LDA. Unlike LDA, the HTMM is capable of modeling dependency among the latent topics in a corpus of documents. The topic distributions can be used for a variety of goals including identification of similar documents, network analysis, and identification of key topics in a corpus. The HTMM and related topic models offer a fully probabilistic statistical framework for modeling textual data that often results from open-ended questionnaires, diaries, interviews, and other information-rich sources of data that cannot be easily analyzed with traditional statistical methods."
summary: ""

featured: false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects: []`.
projects: ["topic-model"]

tags:
- Bayesian
- text mining
- topic model

url_pdf: https://www.psychometricsociety.org/sites/main/files/file-attachments/imps_2018_final_program_f.pdf

math: false

# Cover image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Otherwise, specify the `filename` option to load an image from your `assets/media/` folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  caption: "Directed acyclic graph of the HTMM model."
  focal_point: "Smart"
  preview_only: false
  # alt_text: An optional description of the image for screen readers.
  filename: htmm-dag.png  # Uncomment to load an image from `assets/media/` instead.

# Show recommendations for related content?
show_related: true

# Show breadcrumb navigation?
show_breadcrumb: true

# Hide the navigation bar?
# Often used together with `show_breadcrumb`
header:
  navbar:
    enable: false
---
