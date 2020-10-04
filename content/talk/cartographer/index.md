---
title: Cartographer - Real-Time Loop Closure in 2D LIDAR SLAM
event: ML/Autonomous Navigation Paper Reading Group
event_url: https://www.youtube.com/playlist?list=PLbBjZEwyU7W3lb0U0ZRA95QoKHrh4shX2

location: Online
# address:
#  street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

# summary: Paper Review of Google's Cartographer paper
# abstract: ""

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-06-28T17:00:00Z"
# date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: ["admin"]
tags: ["SLAM", "3D/LiDAR", "Robotics", "Ati"]

# Is this a featured talk? (true/false)
featured: false

image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://google-cartographer-ros.readthedocs.io/en/latest/"
url_pdf: "https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45466.pdf"
url_slides: "https://docs.google.com/presentation/d/16Pk8qRb2RRz58-WDQPH_8c1A2-L2vRBDazlQMqm9TWA/edit?usp=sharing"
url_video: "https://www.youtube.com/watch?v=fUMKAtTRnyM&ab_channel=SabyasachiSahoo"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - internal-project

# Enable math on this page?
math: false
---

In this talk, I review the paper  [Real-Time Loop Closure in 2D LIDAR SLAM](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45466.pdf). In a prior [video](https://www.youtube.com/watch?v=Oo9SsIvyxZA&ab_channel=SabyasachiSahoo), I have also explained the basics of SLAM and gave intuitions required to understand the novel ideas proposed in this paper. The code for Cartographer paper is open sourced [here](https://google-cartographer-ros.readthedocs.io/en/latest/) and widely used and deployed in self driving community for performing accurate LIDAR based SLAM.