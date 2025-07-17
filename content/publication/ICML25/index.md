---
title: "Improving Diversity in Language Models: When Temperature Fails, Change the Loss"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Florian Le Bronnec
- Kunhao Zheng
- Alexandre Allauzen
- Yann Chevaleyre
- Benjamin Negrevergne



date: "2025-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Forty-second International Conference on Machine Learning
publication_short: In *ICML 2025*

abstract: Increasing diversity in language models is a challenging yet essential objective. A common approach is to raise the decoding temperature. In this work, we investigate this approach through a simplistic yet common case to provide insights into why decreasing temperature can improve quality (Precision), while increasing it often fails to boost coverage (Recall). Our analysis reveals that for a model to be effectively tunable through temperature adjustments, it must be trained toward coverage. To address this, we propose rethinking loss functions in language models by leveraging the Precision-Recall framework. Our results demonstrate that this approach achieves a substantially better trade-off between Precision and Recall than merely combining negative log-likelihood training with temperature scaling. These findings offer a pathway toward more versatile and robust language modeling techniques.

# Custom links (uncomment lines below)
links:
- name: OpenReview
  url: 'https://openreview.net/forum?id=RsyMfsqzeG&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICML.cc%2F2025%2FConference%2FAuthors%23your-submissions)'
- name: Google Scholar
  url: 'https://scholar.google.com/citations?view_op=view_citation&hl=fr&user=l_e0zo8AAAAJ&citation_for_view=l_e0zo8AAAAJ:_FxGoFyzp5QC'
url_pdf: https://openreview.net/pdf?id=RsyMfsqzeG
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
