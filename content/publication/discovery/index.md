---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Using Deep Networks for Scientific Discovery in Physiological Signals"
authors: [Tom Beer, Bar Eini-Porat, Sebastian Goodfellow, Danny Eytan, Uri Shalit]
date: 2020-08-26T21:54:37+03:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-26T21:54:37+03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
# publication: "Using Deep Networks for Scientific Discovery in Physiological Signals"
publication_short: ""

abstract: "Deep neural networks (DNN) have shown remarkable success in the classification of physiological signals. In this study we propose a method for examining to what extent does a DNN's performance rely on rediscovering existing features of the signals, as opposed to discovering genuinely new features. Moreover, we offer a novel method of removing a hand-engineered feature from the network's hypothesis space, thus forcing it to try and learn representations which are different from known ones, as a method of scientific exploration. We then build on existing work in the field of interpretability, specifically class activation maps, to try and infer what new features the network has learned. We demonstrate this approach using ECG and EEG signals. With respect to ECG signals we show that for the specific task of classifying atrial fibrillation, DNNs are likely rediscovering known features. We also show how our method could be used to discover new features, by selectively removing some ECG features and rediscovering them. We further examine how could our method be used as a tool for examining scientific hypotheses. We simulate this scenario by looking into the importance of eye movements in classifying sleep from EEG. We show that our tool can successfully focus a researcher's attention by bringing to light patterns in the data that would be hidden otherwise."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2008.10936
url_code: https://github.com/tom-beer/deep-scientific-discovery
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
