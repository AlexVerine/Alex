---
title: "Preprint: Training Normalizing Flows with the Precision-Recall Divergence"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Benjamin Negrevergne
- Yann Chevaleyre
- Muni Sreenivas Pydi


date: "2023-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: Arxiv pre-print

abstract: Generative models can have distinct mode of failures like mode dropping and low quality samples, which cannot be captured by a single scalar metric. To address this, recent works propose evaluating generative models using precision and recall, where precision measures quality of samples and recall measures the coverage of the target distribution. Although a variety of discrepancy measures between the target and estimated distribution are used to train generative models, it is unclear what precision-recall trade-offs are achieved by various choices of the discrepancy measures. In this paper, we show that achieving a specified precision-recall trade-off corresponds to minimising -divergences from a family we call the  *PR-divergences*. Conversely, any -divergence can be written as a linear combination of PR-divergences and therefore correspond to minimising a weighted precision-recall trade-off. Further, we propose a novel generative model that is able to train a normalizing flow to minimise any -divergence, and in particular, achieve a given precision-recall trade-off.


# Custom links (uncomment lines below)
links:
- name: arXiv
  url: 'https://arxiv.org/abs/2302.00628'
- name: Google Scholar
  url: 'https://scholar.google.com/citations?view_op=view_citation&hl=en&user=l_e0zo8AAAAJ&citation_for_view=l_e0zo8AAAAJ:u-x6o8ySG0sC'
url_pdf: 'https://arxiv.org/pdf/2302.00628.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
