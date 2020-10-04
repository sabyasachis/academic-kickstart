---
title: Car Image Masking
summary: Remove the background from car images
tags:
- Deep Learning
- Computer Vision
- Segmentation
date: "2017-09-30T00:00:00Z"

math: true

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Image adapted from [Carvana](https://www.kaggle.com/c/carvana-image-masking-challenge)
  focal_point: Smart

url_code: "https://github.com/sabyasachis/car-image-masking"
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
links : [{name : "Kaggle", url : "https://www.kaggle.com/c/carvana-image-masking-challenge"}]

---

* Automatically identify the boundaries of the car in an image
* Implemented U net in keras and whose mean dice coefficient was 0.9963

