---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Selective Randomization Inference for Adaptive Experiments"
authors:
- admin
- Qingyuan Zhao
- Zijun Gao
date: "2024-10-29T09:18:35Z"
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

abstract: Adaptive experiments use preliminary analyses of the data to inform further course of action and are commonly used in many disciplines including medical and social sciences. Because the null hypothesis and experimental design are not pre-specified, it has long been recognized that statistical inference for adaptive experiments is not straightforward. Most existing methods only apply to specific adaptive designs and rely on strong assumptions. In this work, we propose selective randomization inference as a general framework for analysing adaptive experiments. In a nutshell, our approach applies conditional post-selection inference to randomization tests. By using directed acyclic graphs to describe the data generating process, we derive a selective randomization p-value that controls the selective type-I error without requiring independent and identically distributed data or any other modelling assumptions. We show how rejection sampling and Markov Chain Monte Carlo can be used to compute the selective randomization p-values and construct confidence intervals for a homogeneous treatment effect. To mitigate the risk of disconnected confidence intervals, we propose the use of hold-out units. Lastly, we demonstrate our method and compare it with other randomization tests using synthetic and real-world data.

# Summary. An optional shortened abstract.
summary: ""

tags:
- Source Themes
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'https://arxiv.org/pdf/2405.07026'
url_code:
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
