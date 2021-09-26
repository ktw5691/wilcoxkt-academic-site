---
draft: false

title: "Integrating text into psychological and education research: Latent variable modeling and applications"
event: Quantitative Methods Colloquium, Department of Psychology
event_url: 

location: Vanderbilt University
address:
  street:
  city: Nashville
  region: TN
  postcode:
  country: United States

abstract: "Text has a long history in psychological and education research, but appropriate quantitative methods are surprisingly underdeveloped. In this talk, I introduce a latent variable measurement modeling framework for text, topic modeling, that has been recently applied in psychology and education. Researchers have tried to link these latent variables (topics) from text to other measures in a regression framework using a two-stage approach. Two-stage approaches with latent variable models, however, can be problematic. I will discuss a new model I developed that addresses this research gap by extending supervised topic modeling to incorporate covariates and latent topics to model an outcome. I will describe a Bayesian estimation algorithm and R package to fit the proposed model. I will also present results from a simulation study evaluating the two-stage approach and the proposed model. Finally, I will demonstrate this approach in a study of emotional dysregulation and interpersonal conflict in the context of nonsuicidal self-injury."
summary: "Invited Talk"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-09-13"
date_end: "2021-09-13"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2021-09-26T00:00:00Z"

authors:
- admin

tags:
- SLDAX
- topic modeling
- Bayesian
- text mining

# Is this a featured talk? (true/false)
featured: false

# Optional header image (relative to `assets/media/` folder)
# header:
#   caption:
#   image: "ex-topics-simplex.png"

# image:
#   caption: 'Directed acylic graphical representation of an SLDAX model with a Gaussian outcome.'
#   focal_point: Smart  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: "./slides/2021vanderbilt-wilcox-slides.pdf"
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

{{< figure src="ex-topics-simplex.png" caption="Topic proportion estimates for interpersonal conflict narratives." numbered="false" >}}
