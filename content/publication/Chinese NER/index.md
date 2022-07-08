---
title: 'Token Relation Aware Chinese Named Entity Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wenge Rong
  - Xiaofeng Zhang
  - Yuanxin Ouyang
  - Chenghua Lin
  - Zhang Xiong

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: 'April 2022'
doi: 'https://doi.org/10.1145/3531534'

# Schedule page publish date (NOT publication's date).

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Asian and Low-Resource Language Information Processing
# publication_short: In *ICW*

abstract: Due to the lack of natural delimiters, most Chinese Named Entity Recognition (NER) approaches are character-based and utilize an external lexicon to leverage the word-level information. Although they have achieved promising results, the latent words they introduced are still non-contextualized. In this paper, we investigate three relations, i.e, adjacent relation between characters, character co-occurrence relation between latent words, and dependency relation among tokens, to address this issue. Specifically, we first establish the local context for latent words and then propose a masked self-attention mechanism to incorporate such local contextual information. Besides, since introducing external knowledge such as lexicon and dependency relation inevitably brings in some noises, we propose a gated information controller to handle this problem. Extensive experimental results show that the proposed approach surpasses most similar methods on public datasets and demonstrates its promising potential.

# Summary. An optional shortened abstract.
summary: A token relation aware Chinese Named Entity Recgnition Framework.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/10.1145/3531534'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

