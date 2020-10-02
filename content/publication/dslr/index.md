+++
title = "DSLR : Dynamic to Static LiDAR scan Reconstruction using adversarially trained autoencoder"
date = 2020-09-01T00:00:00

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
publication = "AAAI 2021 (conference submission)"
publication_short = ""

# Abstract.
abstract = "Uncovering the static environment in presence of dynamic objects e.g vehicles, pedestrians, is essential for autonomous navigation. While this problem of dynamic to static translation (DST) has been recently explored for images and point cloud data, no work has been attempted to solve DST for LiDAR scans. We adapt non-LIDAR based DST methods and existing 3D reconstruction based methods for DST on LiDAR scan and show that they perform sub-optimally. We hypothesize that this poor performance can be attributed to the reasons that range image based models perform superior to point cloud based models and the adapted adversarial methods work directly on pixel/point space instead of latent space. To address the above challenges, we propose DSLR, which works on range image based LiDAR data and uses an adversarially trained auto encoder via an input pair based discriminator. DSLR uses an adversarial loss to learn DST mapping on latent space instead of range image space. DSLR is also the first solution for DST that generates static scan without using any  segmentation information which is tedious to manually annotate for new environment. Additionally, we propose a novel data collection algorithm to extract corresponding static-dynamic pairs from random runs. DSLR gives state of the art performance on simulated and real world datasets and also shows at least 4x improvement on Chamfer distance. We demonstrate the potential of our results by showing that DSLR is the only practically viable model which has its reconstruction quality falling within the tolerable limits for autonomous navigation based downstream tasks like SLAM in dynamic environments."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
# doi = "10.1038/s41598-020-61289-4"

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

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
url_pdf = "https://drive.google.com/file/d/1rw9E18UyXAH2mDCkLtK6CFpk8ftRIF0c/view?usp=sharing"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
# For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Supplementary Material", url = "https://static-content.springer.com/esm/art%3A10.1038%2Fs41598-020-61289-4/MediaObjects/41598_2020_61289_MOESM1_ESM.pdf"},
#{name = "Poster (earlier version)", url = "PosterA0.pdf"}]

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