+++
title = "Hierarchical Task Mapping on Dragonfly topology for scaling Molecular Dynamics"
date = 2016-07-30T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin", "Sathish S. Vadhiyar"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["5"]

# Publication name and optional abbreviated version.
publication = "Master's Thesis"
publication_short = ""

# Abstract.
abstract = "Molecular Dynamics (MD) performs non-uniform computations and communications that vary over space and time. LAMMPS is one of the leading MD packages used extensively by molecular dynamics community. With the advent of exascale systems, it becomes important to ensure good scalability on large number of cores. Dragonfly topology is one of the most promising network topologies for the exascale era due to their scalability and cost. Despite having multiple advantages like non-minimal routing in Cray, communication is a major bottleneck for the scalability of LAMMPS. In this work, we propose strategies for efficient communications in LAMMPS MD simulations on dragonfly network topology. In particular, we propose partitioning-based task mapping algorithm, which along with considering the hierarchical nature of topology, also tries to account for non-minimal routing, non-contiguous job allocations and possible contentions at intra-node or intra-socket level. We compare our mapping with open source mapping software HierTopoMap and NUMA mapping from LAMMPS and show that our mapping algorithm reduces communication time by more than 15% in general and maximum of 44% on 8016 cores. While we had applied our strategy to dragonfly topology, our work is also applicable to general hierarchical topologies."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
# doi = "10.1038/s41598-020-61289-4"

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Parallel Progromming", "MPI", "Molecular Dynamics"]

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
url_pdf = "https://drive.google.com/file/d/1ldhK5Sejsc5kUBU3xJO1fvSvty0Ezps9/view?usp=sharing"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = "http://scholar.google.com/scholar?cluster=4824188381298024934&hl=en&oi=scholarr"
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