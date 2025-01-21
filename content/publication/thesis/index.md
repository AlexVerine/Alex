---
title: "Quality and Diversity in Generative Models through the lens of f-divergences"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

date: "2024-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Thesis of Philosophiae Doctor (PhD)
publication_short: PhD Thesis

abstract: Generative modeling have become an essential tool in machine learning for generating realistic samples from complex data distributions. Despite significant advancements in models such as Generative Adversarial Networks , Variational Autoencoders, Normalizing Flows, and Diffusion models, challenges persist in achieving a balance between sample quality and sample diversity. Precision and recall have emerged as crucial metrics for assessing the quality and diversity of generative models. Precision measures how many generated samples are coherent with the real data distribution, reflecting sample quality. Recall evaluates how many samples from the real data distribution can be generated, indicating sample diversity. This thesis addresses the fundamental problem of characterizing, tuning, and improving Precision and recall in generative models. The first major contribution of this work is the unification of precision and recall definitions within the framework of f-divergences. By expressing the most popular metrics and their derivatives as f-divergences, we establish a cohesive and comprehensive evaluation system for generative models. This theoretical formulation allows for a clearer understanding and more precise measurement of model performance in terms of quality and diversity. Building upon this theoretical foundation, the thesis introduces a novel method for estimating the f-divergence in a tractable manner, facilitating its use as an objective function in the training of generative models. This approach enables the optimization of a specific trade-off between precision and recall, addressing a critical gap in the current literature where models often fail to achieve an optimal balance due to computational constraints. Furthermore, the thesis proposes an optimal rejection sampling method that enhances both precision and recall. This method is shown to be optimal in terms of any f-divergence, providing a robust technique for refining the outputs of pre-trained generative models. The rejection sampling algorithm is designed to operate under limited computational budgets, making it practical for real-world applications. The experimental validation of the proposed methods is conducted on a variety of datasets, including MNIST, CIFAR-10, Fashion MNIST, CelebA, FFHQ, and ImageNet. Using both Normalizing Flows, Generative Adversarial Networks and Diffusion Models, we demonstrate the effectiveness of our approaches in tuning the balance between quality and diversity of generated samples, and then in improving the quality. The results highlight the superiority of our methods compared to traditional metrics and existing techniques.

# Custom links (uncomment lines below)
links:
- name: HAL
  url: 'https://theses.hal.science/tel-04677749/'
- name: Google Scholar
  url: 'https://scholar.google.com/citations?view_op=view_citation&hl=fr&user=l_e0zo8AAAAJ&citation_for_view=l_e0zo8AAAAJ:YsMSGLbcyi4C'
url_pdf: https://theses.hal.science/tel-04677749/document
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
