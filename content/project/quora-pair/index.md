---
title: Paraphrase detection on Quora questions
summary: Classify whether question pairs are duplicates or not.
tags:
- Deep Learning
- Machine Learning
- Natural Language Processing
- Paraphrase Detection
date: "2017-06-30T00:00:00Z"

math: true

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Image adapted from [Yinfei Yang](https://ai.googleblog.com/2018/05/advances-in-semantic-textual-similarity.html)
  focal_point: Smart

url_code: "https://github.com/sabyasachis/quora-question-pairs"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Custom links (optional).
# For multiple links, use the form `[{...}, {...}, {...}]`.
links : [{name : "Competition", url : "https://www.kaggle.com/c/quora-question-pairs"}]

---

* Identify question pairs that have the same intent
* Tried LSTM but got 0.489 log loss error using hand tuned features and parameters trained on logistic regression with regularization.

