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
projects:
- topic-model

tags:
- topic model
- Bayesian
- text mining

url_pdf: https://www.psychometricsociety.org/sites/main/files/file-attachments/imps_2018_final_program_f.pdf
url_slides: ""
url_video: ""
url_code: ""

math: false

# Optional header image (relative to `assets/media/` folder)
# header:
#   caption:
#   image: "htmm-dag.png"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: "Directed acyclic graph of the Hidden Topic Markov Model."
#   focal_point: "Smart" # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
---

{{< figure library="true" src="htmm-dag.png" title="Directed acyclic graph of the Hidden Topic Markov Model." >}}
