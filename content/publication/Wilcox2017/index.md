---
title: "Bayesian hidden topic Markov models"
authors:
- admin
date: "2017-05-11"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-05-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Recent developments in topic modeling for text corpora have incorporated Markov models in the latent space to better learn contextual content. Known as the Hidden Topic Markov Model (HTMM), this natural extension of probabilistic mixture models relaxes the \"bag-of-words\" assumption of the foundational latent Dirichlet allocation topic model by allowing the discrete latent variables, or topics, to follow a special first-order Markov process. Parameter estimation is performed using an expectation-maximization (EM) algorithm with fixed dimensionality of the topic space (Gruber, Rosen-Zvi, and Weiss 2007). I fully derive the state space and EM algorithm for the HTMM. I then extend the Hidden Topic Markov Model (HTMM) into a fully Bayesian framework using a Gibbs sampler. The necessary full conditional distributions are derived and a Gibbs sampling algorithm proposed. I implement both the HTMM EM algorithm (Gruber, Rosen-Zvi, and Weiss 2007) and the HTMM Gibbs sampling algorithm in the R and C++ programming languages. The performance of both inferential algorithms is evaluated on twelve simulated data sets and on a collection of proceedings from the Conference on Neural Information Processing Systems (NIPS). The results suggest that the Gibbs sampling algorithm provides better recovery of the topic space than a combination of the EM and Viterbi algorithms. Parameter estimation is comparable using point estimates with both algorithms. The convergence of the Gibbs sampler is studied and is reliable for reasonably large data sets. Evaluation of both algorithms on the NIPS corpus suggests that the HTMM is better able to handle polysemy than LDA and provides coherent and contiguous topics. Predictive accuracy measured by perplexity is better on training and test documents using the HTMM than using LDA on the NIPS corpus. Introducing Markovian dynamics in topical space provides better topical segmentation of a corpus and increased predictive accuracy for unseen documents.

# Summary. An optional shortened abstract.
summary: ""

tags: 
- Gibbs sampler
- hidden Markov models
- hierarchical Bayes
- latent variable modeling
- mixture models
- natural language processing
- text mining
- topic modeling
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://scholarworks.rit.edu/theses/9443/
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Optional header image (relative to `assets/media/` folder)
# header:
#   caption:
#   image: "htmm-dag.png"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Hidden topic Markov model.'
#   focal_point: "Center"
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- topic-model

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{< figure library="true" src="htmm-dag.png" title="Directed acyclic graph of the HTMM model." >}}
