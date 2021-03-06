---
title: "Adversarial Focal Loss: Asking Your Discriminator for Hard Examples"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Anonymous

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-05-19T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Under Review
publication_short: Under Review

abstract: Focal Loss has reached incredible popularity as it uses a simple technique to identify and utilize hard examples to achieve better performance on classification. However, this method does not easily generalize outside of classification tasks, such as in keypoint detection. In this paper, we propose a novel adaptation of Focal Loss for keypoint detection tasks, called Adversarial Focal Loss (AFL). AFL not only is semantically analogous to Focal loss, but also works as a plug-and-chug upgrade for arbitrary loss functions. While Focal Loss requires output from a classifier, AFL leverages a separate adversarial network to produce a difficulty score for each input. This difficulty score can then be used to dynamically prioritize learning on hard examples, even in absence of a classifier. In this work, we show AFL's effectiveness in enhancing existing methods in keypoint detection and verify its capability to re-weigh examples based on difficulty.

# Summary. An optional shortened abstract.
summary: We proposed a generalizable adaptation of Focal Loss to keypoint detection leveraging difficulty scores from a discriminator.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Preprint Online (Free Download)
  url: https://arxiv.org/pdf/2207.07739.pdf

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
image:
  caption:
  focal_point: ""
  preview_only: false

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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
