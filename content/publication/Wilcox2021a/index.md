---
title: "Modeling approaches for cross-sectional
integrative data analysis: Evaluations and recommendations"
authors:
- admin
- Lijuan Wang

date: "2021-07-29"
doi: 10.1037/met0000397

# Schedule page publish date (NOT publication's date).
# publishDate: "2021-01-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

math: true

# Publication name and optional abbreviated publication name.
publication: "*Psychological Methods*"
publication_short: ""

abstract: 'Integrative data analysis (IDA) jointly models participant-level data from multiple studies. In psychology, IDA has been conducted using different fixed-effects and multilevel modeling (MLM) approaches. However, evaluations regarding the performance of these models in an IDA context are limited. The goal of this article is to evaluate three fixed-effects models (aggregated vs. disaggregated vs. study-specific coefficients regressions) and two MLMs (fixed-slope vs. random-slopes MLM) for cross-sectional IDA. Using a simulation study with study sample sizes and numbers of studies consistent with applied IDA (e.g., 2--35 studies), we evaluated estimation bias and Type I error rates for participant-level and study-level effects and variance components for these models; for the MLMs, we evaluated different estimation methods (i.e., constrained vs. unconstrained variance estimation and five degrees of freedom methods). Disaggregated and study-specific coefficients regressions and both MLMs yielded fixed effects estimates with ignorable bias, but only the random-slopes MLM fully modeled between-study heterogeneity and, consequently, provided well-controlled Type I error rates for testing both fixed effects. Overall, we found that MLMs could be feasible under IDA conditions with three to six studies and well-chosen estimation methods. A real-data IDA example is used to illustrate and compare the application of the five models. We hope our results will help researchers choose appropriate
modeling methods when conducting IDA.'

summary: "Integrative data analysis (IDA) is an alternative to meta-analysis that combines participant-level data from multiple studies. Two approaches, fixed effects models (FEM) and multilevel models (MLM), have been used in psychological applications of IDA, but have not been fully evaluated. Because IDA combines data from multiple studies, two different kinds of fixed effects can be studied in IDA: study-level and participant-level effects. Furthermore, between-study differences need to be modeled carefully. For IDA with cross-sectional data, we reviewed three FEMs and two MLMs. We focused on (a) whether and how they can estimate and test participant-level and study-level fixed effects; and (b) whether and how they model between-study differences in study means and participant-level effects. Because IDA is typically conducted with fewer than 30 studies, we evaluated the performance of these models and different MLM estimation methods in a simulation study under realistic IDA conditions. While two of the FEMs accurately estimate the fixed effects, they do not model between-study differences in participant-level effects, leading to incorrect inferences. Only a random-slopes MLM that accounts for differences in both study means and participant-level effects provided accurate inferences and estimates of the fixed effects and between-study differences. We found that MLMs can be feasible for IDA with as few as three to six studies using appropriate estimation methods. We illustrated the application of the five models and how they can provide different estimates and inferences in an empirical example. We conclude with recommendations to guide researchers when planning an IDA."

tags:
- integrative data analysis
- cumulative data analysis
- multilevel modeling
- disaggregation of study-level and participant-level effects
- degrees of freedom methods

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Type I error rate for the average participant-level fixed effect, $\\gamma_W$, for each model (rows) as a function of the number of studies, the average study sample size (columns), and the effect size of the slope variance $f^2\\left(\\sigma^2_{u_1}\\right)$. Horizontal dashed lines represent upper (0.075) and lower (0.025) bounds for acceptable Type I error rate. D LR = disaggregated linear regression; SSC LR = study-specific coefficients linear regression; FS MLM = fixed-slope MLM; RS MLM = random-slopes MLM; BW = between-within; C/R = containment/residual; KR = Kenward-Roger; S = Satterthwaite."
  focal_point: "Smart"  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- integrative-data-analysis

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
