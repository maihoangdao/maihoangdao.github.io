---
title: "VinAI at ChEMU 2020: An accurate system for named entity recognition in chemical reactions from patents"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Dat Quoc Nguyen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The Working Notes of Conference and Labs of the Evaluation Forum 2020*
publication_short: In *The Working Notes of CLEF 2020*

abstract: "This paper describes our VinAI system for the ChEMU task 1 of named entity recognition (NER) in chemical reactions. Our system employs a BiLSTM-CNN-CRF architecture [6] with additional contextualized word embeddings. It achieves very high performance, officially ranking second with regards to both exact- and relaxed-match F1 scores at 94.33% and 96.84%, respectively. In a post-evaluation phase, fixing a mapping bug which converts the column-based format into the brat standoff format helps our system to obtain higher results. In particular, we obtain an exact-match F1 score at 95.21% and especially a relaxed-match F1 score at 97.26%, thus achieving the highest relaxed-match F1
compared to all other participating systems. We believe our system can serve as a strong baseline for future research and downstream applications of chemical NER over chemical reactions from patents."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Named Entity Recognition, Chemical reactions, Patents, Neural network]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://ceur-ws.org/Vol-2696/paper_231.pdf'
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
# #   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
