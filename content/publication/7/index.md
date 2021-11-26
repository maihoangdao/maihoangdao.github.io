---
title: "COVID-19 Named Entity Recognition for Vietnamese"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
  - Thinh Hung Truong
  - admin
  - Dat Quoc Nguyen

# Author notes (optional)

# author_notes:

# - "Equal contribution"

# - "Equal contribution"

date: "2021-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).

publishDate: "2017-01-01T00:00:00Z"

# Publication type.

# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;

# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;

# 7 = Thesis; 8 = Patent

publication_types: ["1"]

# Publication name and optional abbreviated publication name.

publication: "In _The 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_"
publication_short: In *NAACL 2021*

abstract: "The current COVID-19 pandemic has lead to the creation of many corpora that facilitate NLP research and downstream applications to help fight the pandemic. However, most of these corpora are exclusively for English. As the pandemic is a global problem, it is worth creating COVID-19 related datasets for languages other than English. In this paper, we present the first manuallyannotated COVID-19 domain-specific dataset for Vietnamese. Particularly, our dataset is annotated for the named entity recognition (NER) task with newly-defined entity types that can be used in other future epidemics. Our dataset also contains the largest number of entities compared to existing Vietnamese NER datasets. We empirically conduct experiments using strong baselines on our dataset, and find that: automatic Vietnamese word segmentation helps improve the NER results and the highest performances are obtained by finetuning pre-trained language models where the monolingual model PhoBERT for Vietnamese (Nguyen and Nguyen, 2020) produces higher results than the multilingual model XLM-R (Conneau et al., 2020). We publicly release our dataset at: https://github.com/VinAIResearch/PhoNER_COVID19."

# Summary. An optional shortened abstract.

# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Named Entity Recognition, COVID-19 Pandemic, Vietnamese]

# Display this page in the Featured widget?

featured: false

# Custom links (uncomment lines below)

# links:

# - name: Custom Link

# url: http://example.org

url_pdf: "https://aclanthology.org/2021.naacl-main.173.pdf"
url_code: ""
url_dataset: "https://github.com/VinAIResearch/PhoNER_COVID19"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder.

# image:

# caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'

# focal_point: ""

# preview_only: false

# # Associated Projects (optional).

# # Associate this publication with one or more of your projects.

# # Simply enter your project's folder or file name without extension.

# # E.g. `internal-project` references `content/project/internal-project/index.md`.

# # Otherwise, set `projects: []`.

# projects:

# - example

# # Slides (optional).

# # Associate this publication with Markdown slides.

# # Simply enter your slide deck's filename without extension.

# # E.g. `slides: "example"` references `content/slides/example/index.md`.

# # Otherwise, set `slides: ""`.

# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
