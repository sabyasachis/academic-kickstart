---
title: Global NIPS Paper Implementation Challenge
summary: Implementation of the paper titled, Thy Friend is My Friend Iterative Collaborative Filtering for Sparse Matrix Estimation.
tags:
- Recommender System

date: "2018-01-30T00:00:00Z"

math: true

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Image adapted from [Buomsoo Kim](https://buomsoo-kim.github.io/recommender%20systems/2020/05/30/Recommender-systems-collab-filtering-1.md/)
  focal_point: Smart

url_code: "https://github.com/sabyasachis/thyFriendMyFriend"
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
links : [{name : "Winner Interview", url : "https://medium.com/nurture-ai/sabyasachi-sahoo-bringing-nlp-and-rl-together-65e135cd48e1"},
{name : "Competition", url : "https://www.facebook.com/nurtureai/posts/127818904594905"}]

---

My primary motivation to implement this paper “Thy Friend Is My Friend: Iterative Collaborative Filtering for Sparse Matrix Estimation” was to understand how recommendation systems work. The paper talks about a new way of user-item prediction in recommender systems for extremely sparse datasets. After reading the dataset, we make sure the dataset has been made symmetric and the values are normalised. In step 1, we divide the user-item rating pairs randomly into three parts and use each part in next 3 steps. In step 2, we take first part and calculate neighbourhood vector for every vertex i.e. get the product along the shortest path from given vertex to every possible vertex. In step 3, we use part 2 obtained and use it to calculate distance between any two vertices (like user and movie) as an inner product between r-hop and r+1 hop neighbourhood vector. In step 4, we average over all vertices within a distance threshold to predict user-item rating.

To test validity of the code, we experimentally showed that for recommendation dataset,

if
$$p > 1/n$$
where $p$ is sparsity and $n$ is dimension of the matrix,

then Mean Square Error of the algorithm in the paper (and our implementation) is bounded by
$$MSE < O((pn)^{-1/5})$$

