---
title: "MaskEval: Weighted MLM-Based Evaluation for Text Summarization and Simplification"
authors:
- admin
- Rachel Bawden
- Thomas Scialom
- Benoît Sagot
- Jackie Chi Kit Cheung

date: "2022-10-13"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-06"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arXiv Preprint"
publication_short: ""

abstract: In text summarization and simplification, system outputs must be evaluated along multiple dimensions such as relevance, factual consistency, fluency, and grammaticality, and a wide range of possible outputs could be of high quality. These properties make the development of an adaptable, reference-less evaluation metric both necessary and challenging. We introduce MaskEval, a reference-less metric for text summarization and simplification that operates by performing masked language modeling (MLM) on the concatenation of the candidate and the source texts. It features an attention-like weighting mechanism to modulate the relative importance of each MLM step, which crucially allows it to be adapted to evaluate different quality dimensions. We demonstrate its effectiveness on English summarization and simplification in terms of correlations with human judgments, and explore transfer scenarios between the two tasks. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/2205.12394
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---