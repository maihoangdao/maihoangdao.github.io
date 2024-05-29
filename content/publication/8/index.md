---
title: "From Disfluency Detection to Intent Detection and Slot Filling"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Thinh Hung Truong
  - Dat Quoc Nguyen

# Author notes (optional)
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"

date: "2022-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 23rd Annual Conference of the International Speech Communication Association*
publication_short: In *InterSpeech 2022*

abstract: We present the first empirical study investigating the influence of disfluency detection on downstream tasks of intent detection and slot filling. We perform this study for Vietnamese—a lowresource language that has no previous study as well as no public dataset available for disfluency detection. First, we extend the fluent Vietnamese intent detection and slot filling dataset PhoATIS by manually adding contextual disfluencies and annotating them. Then, we conduct experiments using strong baselines for disfluency detection and joint intent detection and slot filling, which are based on pre-trained language models. We find that (i) disfluencies produce negative effects on the performances of the downstream intent detection and slot filling tasks, and (ii) in the disfluency context, the pre-trained multilingual language model XLM-R helps produce better intent detection and slot filling performances than the pre-trained monolingual language model PhoBERT, and this is opposite to what generally found in the fluency context.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [ Disfluency Detection; Intent Detection; Slot Filling; Vietnamese; Low-resource Language]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://www.isca-archive.org/interspeech_2022/dao22_interspeech.pdf"
url_code: "https://github.com/VinAIResearch/PhoATIS_Disfluency"
url_dataset: "https://github.com/VinAIResearch/PhoATIS_Disfluency"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
