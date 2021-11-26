---
title: "APT attack detection based on flow network analysis techniques using deep learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Cho Do Xuan
- admin
- Hoa Dinh Nguyen

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-10-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Intelligent & Fuzzy Systems*
publication_short: In *Journal of Intelligent & Fuzzy Systems*

abstract: Advanced Persistent Threat (APT) attacks are a form of malicious, intentionally and clearly targeted attack. This attack technique is growing in both the number of recorded attacks and the extent of its dangers to organizations, businesses and governments. Therefore, the task of detecting and warning APT attacks in the real system is very necessary today. One of the most effective approaches to APT attack detection is to apply machine learning or deep learning to analyze network traffic. There have been a number of studies and recommendations to analyze network traffic into network flows and then combine with some classification or clustering methods to look for signs of APT attacks. In particular, recent studies often apply machine learning algorithms to spot the present of APT attacks based on network flow. In this paper, a new method based on deep learning to detect APT attacks using network flow is proposed. Accordingly, in our research, network traffic is analyzed into IP-based network flows, then the IP information is reconstructed from flow, and finally deep learning models are used to extract features for detecting APT attack IPs from other IPs. Additionally, a combined deep learning model using Bidirectional Long Short-Term Memory (BiLSTM) and Graph Convolutional Networks (GCN) is introduced. The new detection model is evaluated and compared with some traditional machine learning models, i.e. Multi-layer perceptron (MLP) and single GCN models, in the experiments. Experimental results show that BiLSTM-GCN model has the best performance in all evaluation scores. This not only shows that deep learning application on flow network analysis to detect APT attacks is a good decision but also suggests a new direction for network intrusion detection techniques based on deep learning.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Advanced Persistent Threat, APT Attack Detection, Network Traffic, Bidirectional Long-short Term Memory,
Graph Convolutional Networks]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
