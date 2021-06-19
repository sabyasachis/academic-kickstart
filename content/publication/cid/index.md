+++
title = "Improving Automatic Concept Extraction on Chest X-Rays"
date = 2021-06-10T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin", "Rachit Shah", "Abhinav Jain", "Chiranjib Bhattacharyya"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "In Progress"
publication_short = ""

# Abstract.
# abstract = ""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
# doi = "10.1038/s41598-020-61289-4"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Deep Learning", "Computer Vision", "Explainability", "AI for healthcare", "Segmentation", "Classification"]

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
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "https://docs.google.com/presentation/d/1Dc53DnZ4lZiAjBWvNEVomt8vEHqrJ0sNqnYZQJmaSbs/edit?usp=sharing"
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
  caption = "The bottom row of each concept cluster (denoted by dotted lines) shows the origial image of the class. It also contains a yellow contour highlighting the concept patch in the image. The top row shows the zoomed-in image of this concept patch."
  # caption = "Images adapted from [ACE](https://arxiv.org/abs/1902.03129) and [TCAV](https://beenkim.github.io/slides/TCAV_ICML_pdf.pdf)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "BottomLeft"

+++

(a) Patterns (or abstract concepts) identified by AIIMS as COVID-19 features. Can we extract them from a COVID-19 Dataset using a pre-trained model? Yes, using Automatic Concept Extraction or ACE. Next, we run ACE on a PASCAL VOC dataset to demonstrate its effectiveness for extracting such concepts automatically from a dataset and a pre-trained model and also evaluate its concept extraction performance.

(b) Here, we run ACE to extract high-level concepts for the "Garbage-Truck" class and show the top 3 extracted concept clusters using ACE. The top 3 extracted concepts are "road", "sky", and "road" for "Garbage Truck". But these are not the concepts that humans typically look for to identify garbage trucks. Can we improve the concept extraction? Yes. Our proposed approach attempts to address most of the problems in ACE.

(c) Here, we show that the top 3 concepts identified by our method for the "Garbage-Truck" class are "body of the truck", "trees", and "rear-view mirror". And these are the concepts that humans also look for while trying to identify a garbage truck. And these concepts were extracted only using a pre-trained model and classification dataset.

As a next step, we will use our proposed approach on medical imaging datasets to extract COVID-19 concepts and get it validated by radiologists.

This is an ongoing research project. If this sounds interesting, for further details or future collaboration opportunities, please contact me.