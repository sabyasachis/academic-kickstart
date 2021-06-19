+++
title = "DCT-VAE: Capturing Low level and High Level features for image generation"
date = 2021-06-09T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Tezuesh Varshney", "admin", "Chiranjib Bhattacharyya"]

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
tags = ["Deep Learning", "Computer Vision", "Generative Modelling"]

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
url_slides = "https://drive.google.com/file/d/1mGqLqsLcy-DR9tHKfe9QArfWA_2v8nZx/view?usp=sharing"
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
  caption = "DCT-VAE motivation and results"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "BottomLeft"

+++

(a) What is DCT? Figure (a) shows how f(x,y), an image in spatial domain, can be converted to F(u,v), in frequency domain, using Discrete Cosine Transform or DCT. The original image f(x,y) can be exactly recovered from F(u,v), the image in frequency domain, using inverse DCT or IDCT.

(b) What does it mean to convert an original image to DCT matrix? Figure (b) shows the frequency in black and white, corresponding to each element in DCT matrix. The numbers are the elements of the DCT matrix and denote the coefficients for the frequency. They are obtained after applying DCT on original images. We can see that upper left elements of the DCT matrix correspond to low frequency. As we go down and towards right, we see the elements of DCT matrix corresponding to higher frequencies gradually.

(c) Why do we care about different frequencies of original images? Figure (c) shows that as we go from left to right, we add higher frequency details to the image, which results in increasing image quality or resolution of the image. In other words, low frequency features (images at the left) captures the global features of the image, like face of a woman. The high frequency features (images at the right) correspond to the local features of the image like texture of eyes or hair, that helps it to build a higher quality image.

(d) How can we use DCT to extract these global and local features? Let *k* be an anti-diagonal level in DCT matrix. In the top row images, the non-zero DCT matrix elements are shown in black, whereas the masked-out elements of the DCT matrix have been shown in white.  The frequency at a given level is more or less same, as seen in Figure (b). This implies that all the elements at a given level of *k* contain similar abstract information about the image. Now coming back to figure (d), as we go from left to right for the top row of images, we add a new level *k* or more local features to our image. And in the bottom row of images, starting from the most high level feature of the image, the image of Barack Obama becomes increasingly sharp due to increasing local features. Therefore, the different levels of *k* in a DCT matrix constitutes the global or local features of the image.


(e) What can we do with these global and local features of an image? The main goal of high quality image generation is to learn these global and local features accurately. This has been solved in literature in two paradigms: (1) There are different models that specialize in learning the global or local features and they are trained jointly (like in VAE + Autoregressive models). (2) The model implicitly learns about the global and local features in different levels of hierarchy (like in Hierarchical VAE). But in both these paradigms, the models have to learn about global and local features of the images without access to these features. In Figure (e), we show that our proposed approach can improve the performance of any image generation model by explicitly using the global and local features. In this figure, we show that compared to Vanilla VAE (2nd row) and Perceptual VAE (3rd row), our approach helps the model to learn the global and local features accurately. Specifically, we can see that hairs and eyes of the faces generated by our approach are much sharper than the baselines.



This is an ongoing research project. If this sounds interesting, for further details or future collaboration opportunities, please contact me.