---
title: "A novel approach for APT attack detection based on combined deep learning model"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Cho Do Xuan
  - admin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Neural Computing and Applications*
publication_short: In *Journal of Neural Computing and Applications*

abstract: "Advanced persistent threat (APT) attack is a malicious attack type which has intentional and clear targets. This attack technique has become a challenge for information security systems of organizations, governments, and businesses. The approaches of using machine learning or deep learning algorithms to analyze signs and abnormal behaviors of network traffic for detecting and preventing APT attacks have become popular in recent years. However, the APT attack detection approach that uses behavior analysis and evaluation techniques is facing many difficulties due to the lack of typical data of attack campaigns. To handle this situation, recent studies have selected and extracted the APT attack behaviors which based on datasets are built from experimental tools. Consequently, these properties are few and difficult to obtain in practical monitoring systems. Therefore, although the experimental results show good detection, it does not bring high efficiency in practice. For above reasons, in this paper, a new method based on network traffic analysis using a combined deep learning model to detect APT attacks will be proposed. Specifically, individual deep learning networks such as multilayer perceptron (MLP), cnvolutional neural network (CNN), and long short-term memory (LSTM) will also be sought, built and linked into combined deep learning networks to analyze and detect signs of APT attacks in network traffic. To detect APT attack signals, the combined deep learning models are performed in two main stages including (i) extracting IP features based on flow: In this phase, we will analyze network traffic into networking flows by IP address and then use the combined deep learning models to extract IP features by network flow; (ii) classifying APT attack IPs: Based on IP features extracted in a task (i), the APT attack IPs and normal IPs will be identified and classified. The proposal of a combined deep learning model to detect APT attacks based on network traffic is a new approach, and there is no research proposed and applied yet. In the experimental section, combined deep learning models proved their superior abilities to ensure accuracy on all measurements from 93 to 98%. This is a very good result for APT attack detection based on network traffic."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  [
    APT Attack Detection,
    Network Traffic,
    Abnormal Behavior,
    Combined Deep Learning Model,
  ]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
# - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
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
