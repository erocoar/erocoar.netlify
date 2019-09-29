+++
# Project title.
title = "rmed"

# Date this page was created.
date = 2019-03-20T00:00:00

# Project summary to display on homepage.
summary = "Computationally efficient repeated median line estimator"

# Tags: can be used for filtering projects.
tags = ["statistics", "robustness", "algorithm"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{icon_pack = "fab", icon = "github", name = "GitHub", url = "https://github.com/erocoar/ggpol"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

`rmed` adds the first implementation in R of the $O(n \log^2 n)$ randomized expected-time algorithm for finding the Repeated Median Line Estimator (Siegel Estimator), following [Matousek and Netanyahu](https://link.springer.com/article/10.1007/PL00009190). It also provides a fast inversion-counting algorithm in $O(n\log n)$ time and implemented in Rcpp that might be of independent interest.

- [rmed on GitHub](https://github.com/erocoar/rmed)
