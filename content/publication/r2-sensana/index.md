---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Optimization-based Sensitivity Analysis for Unmeasured Confounding using Partial Correlations"
authors:
- admin
- Qingyuan Zhao
date: 2024-01-18
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Causal inference necessarily relies upon untestable assumptions; hence, it is crucial to assess the robustness of obtained results to violations of identification assumptions. However, such sensitivity analysis is only occasionally undertaken in practice, as many existing methods only apply to relatively simple models and their results are often difficult to interpret. We take a more flexible approach to sensitivity analysis and view it as a constrained stochastic optimization problem. This work focuses on sensitivity analysis for a linear causal effect when an unmeasured confounder and a potential instrument are present. We show how the bias of the OLS and TSLS estimands can be expressed in terms of partial correlations. Leveraging the algebraic rules that relate different partial correlations, practitioners can specify intuitive sensitivity models which bound the bias. We further show that the heuristic \"plug-in\" sensitivity interval may not have any confidence guarantees; instead, we propose a bootstrap approach to construct sensitivity intervals which perform well in numerical simulations. We illustrate the proposed methods with a real study on the causal effect of education on earnings and provide user-friendly visualization tools.

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'https://arxiv.org/pdf/2301.00040'
url_code: 'https://github.com/tobias-freidling/limosa.beta'
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
