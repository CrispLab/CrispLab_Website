---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Modeling chromatin state from sequence across angiosperms using recurrent convolutional
  neural networks
subtitle: ''
summary: ''
authors:
- Travis Wrightsman
- Alexandre P. Marand
- Peter A. Crisp
- Nathan M. Springer
- Edward S. Buckler
tags: []
categories: []
date: '2021-11-01'
lastmod: 2022-06-01T22:55:51+10:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-06-01T12:55:51.769404Z'
publication_types:
- '2'
abstract: Accessible chromatin regions are critical components of gene regulation
  but modeling them directly from sequence remains challenging, especially within
  plants, whose mechanisms of chromatin remodeling are less understood than in animals.
  We trained an existing deep learning architecture, DanQ, on leaf ATAC-seq data from
  12 angiosperm species to predict the chromatin accessibility of sequence windows
  within and across species. We also trained DanQ on DNA methylation data from 10
  angiosperms, because unmethylated regions have been shown to overlap significantly
  with accessible chromatin regions in some plants. The across-species models have
  comparable or even superior performance to a model trained within species, suggesting
  strong conservation of chromatin mechanisms across angiosperms. Testing a maize
  held out model on a multi-tissue scATAC panel revealed our models are best at predicting
  constitutively-accessible chromatin regions, with diminishing performance as cell-type
  specificity increases. Using a combination of interpretation methods, we ranked
  JASPAR motifs by their importance to each model and saw that the TCP and AP2/ ERF
  transcription factor families consistently ranked highly. We embedded the top three
  JASPAR motifs for each model at all possible positions on both strands in our sequence
  window and observed position- and strand-specific patterns in their importance to
  the model. With our cross-species “a2z” model it is now feasible to predict the
  chromatin accessibility and methylation landscape of any angiosperm genome.
publication: '*bioRxiv*'
url_pdf: https://www.biorxiv.org/content/10.1101/2021.11.11.468292v1
doi: 10.1101/2021.11.11.468292
---
