+++
title = "DSLR : Dynamic to Static LiDAR scan Reconstruction using adversarially trained autoencoder"
date = 2021-02-02T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Prashant Kumar", "admin", "Vanshil Shah", "Vineetha Kondameedi", "Abhinav Jain", "Akshaj Verma", "Chiranjib Bhattacharyya", "Vinay V"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "AAAI 2021"
publication_short = ""

# Abstract.
abstract = "Accurate reconstruction of static environments from LiDAR scans of scenes containing dynamic objects, which we refer to as Dynamic to Static Translation (DST), is an important area of research in Autonomous Navigation. This problem has been recently explored for visual SLAM, but to the best of our knowledge no work has been attempted to address DST for LiDAR scans. The problem is of critical importance due to wide-spread adoption of LiDAR in Autonomous Vehicles. We show that state-of the art methods developed for the visual domain when adapted for LiDAR scans perform poorly. We develop DSLR, a deep generative model which learns a mapping between dynamic scan to its static counterpart through an adversarially trained autoencoder. Our model yields the first solution for DST on LiDAR that generates static scans without using explicit segmentation labels. DSLR cannot always be applied to real world data due to lack of paired dynamic-static scans. Using Unsupervised Domain Adaptation, we propose DSLR-UDA for transfer to real world data and experimentally show that this performs well in real world settings. Additionally, if segmentation information is available, we extend DSLR to DSLR-Seg to further improve the reconstruction quality. DSLR gives the state of the art performance on simulated and real-world datasets and also shows at least 4x improvement. We show that DSLR, unlike the existing baselines, is a practically viable model with its reconstruction quality within the tolerable limits for tasks pertaining to autonomous navigation like SLAM in dynamic environments."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
# doi = "10.1038/s41598-020-61289-4"

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Deep Learning", "Computer Vision", "Generative Modelling", "3D/LiDAR", "Robotics", "SLAM", "Domain Adaptation", "Segmentation", "Ati"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides = "example-slides"

# Links (optional).
url_pdf = "DSLR_paper.pdf"
url_preprint = "https://arxiv.org/abs/2105.12774"
url_code = "https://github.com/dslrproject/dslr/"
url_dataset = "https://github.com/dslrproject/dslr/tree/master/Data"
url_project = "https://dslrproject.github.io/dslr/"
url_slides = "DSLR_slides.pdf"
url_video = "https://www.youtube.com/watch?v=Mi8DNw6F5Mk&t=1s&ab_channel=PRASHANTKUMARPRASHANTKUMAR"
url_poster = "DSLR_poster.pdf"
url_source = ""

# Custom links (optional).
# For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "Appendix PDF", url = "DSLR_appendix.pdf"}, {name="AAAI Conference", url="https://ojs.aaai.org/index.php/AAAI/article/view/16278"}, {name="Results Video", url="https://www.youtube.com/watch?v=xj_JA_Xk-xM&ab_channel=SabyasachiSahoo"}, {name="Teaser Video", url="https://www.youtube.com/watch?v=hHgiC0m5ee0&t=1s"}, {name="Twitter Thread", url="https://twitter.com/saby_tweets/status/1354064595665571840"}]
# ,{name = "Poster (earlier version)", url = "PosterA0.pdf"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  # caption = "Image credit: **Juan David Leongómez 2020**"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "BottomLeft"

+++