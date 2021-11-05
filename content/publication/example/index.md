---
abstract: n the absence of a randomized experiment, a key assumption for drawing
  causal inference about treatment effects is the ignorable treatment
  assignment. Violations of the ignorability assumption may lead to biased
  treatment effect estimates. Sensitivity analysis helps gauge how causal
  conclusions will be altered in response to the potential magnitude of
  departure from the ignorability assumption. However, sensitivity analysis
  approaches for unmeasured confounding in the context of multiple treatments
  and binary outcomes are scarce. We propose a flexible Monte Carlo sensitivity
  analysis approach for causal inference in such settings. We first derive the
  general form of the bias introduced by unmeasured confounding, with emphasis
  on theoretical properties uniquely relevant to multiple treatments. We then
  propose methods to encode the impact of unmeasured confounding on potential
  outcomes and adjust the estimates of causal effects in which the presumed
  unmeasured confounding is removed. Our proposed methods embed nested multiple
  imputation within the Bayesian framework, which allow for seamless integration
  of the uncertainty about the values of the sensitivity parameters and the
  sampling variability, as well as use of the Bayesian Additive Regression Trees
  for modeling flexibility. Expansive simulations validate our methods and gain
  insight into sensitivity analysis with multiple treatments. We use the
  SEER-Medicare data to demonstrate sensitivity analysis using three treatments
  for early stage non-small cell lung cancer. The methods developed in this work
  are readily available in the R package SAMTx.
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - Liangyuan Hu
  - Jungang Zou
  - Chenyang Gu
  - Jiayi Ji
  - Michael Lopez
  - Minal Kale
author_notes: []
publication: In *The Annals of Applied Statistics*
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *AOAS*
url_source: ""
url_video: ""
title: An example conference paper
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
