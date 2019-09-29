+++
# Project title.
title = "bundestag"

# Date this page was created.
date = 2019-09-26T00:00:00

# Project summary to display on homepage.
summary = "Roll call vote data of the German parliament"

# Tags: can be used for filtering projects.
tags = ["dataset", "roll-call-data"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon = "stack-overflow", name = "asd", url = "https://github.com/erocoar/ggpol"}]
#url_custom = [{icon_pack = "fab", icon="github", name="Follow", url = "https://twitter.com/georgecushen"}]
[[url_custom]]
    name = "Custom Link"
    url = "http://www.example.org"

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

`bundestag` is an R library containing all available roll call vote data of the German Bundestag, for the 16th, 17th, 18th and 19th electoral term. Since part of the data is [available in PDF format only](https://www.bundestag.de/parlament/plenum/abstimmung/liste), the data set was created using OCR and lots of manual curation.

- [bundestag on GitHub](https://github.com/erocoar/bundestag)


```r
Observations: 852
Variables: 107
$ `Fraktion/Gruppe` <chr> "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "...
$ Name              <chr> "Andreae", "Beck (Bremen)", "Beck (Köln)", "Behm", "Bender", "Berninger", "Bettin", "Bonde", "Cramon-Taubadel",...
$ Bezeichnung       <chr> "Kerstin Andreae", "Marieluise Beck (Bremen)", "Volker Beck (Köln)", "Cornelia Behm", "Birgitt Bender", "Matthi...
$ `16-80-1`         <chr> "nein", "ja", "ja", "ja", "ja", "ja", "ja", "ja", NA, "ja", NA, "ja", "ja", "ja", NA, "ja", "ja", "ja", "ja", N...
```
