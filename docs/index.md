---
title: Introduction to spatial statistics in R
author: Wesley Brooks
date: "2021-05-04"

github-repo: ucdavisdatalab/YOUR_REPO
url: "https://ucdavisdatalab.github.io/workshop-spatial-stats/"

site: "bookdown::bookdown_site"
knit: "bookdown::render_book"
output:
  bookdown::gitbook:
    config:
      toc:
        before: |
          <li><a href="https://datalab.ucdavis.edu/">
            <img src="https://datalab.ucdavis.edu/wp-content/uploads/2019/07/datalab-logo-full-color-rgb-1.png" style="height: 100%; width: 100%; object-fit: contain" />
          </a></li>
          <li><a href="./" style="font-size: 18px">Introduction to spatial statistics in R</a></li>
        collapse: section
      sharing: no
      view: https://github.com/ucdavisdatalab/workshop-spatial-stats/blob/master/%s
      edit: https://github.com/ucdavisdatalab/workshop-spatial-stats/edit/master/%s
---

# Overview {-}

The key insight  about spatial statistics is that measurements from nearby locations are more alike than measurements from distant locations.

Spatial statistics is a vast subfield with relatively few practitioners. So there has been less development of uniform naming and practices, which can result in a wild-west atmosphere. Let's take a look at the CRAN "Spatial" task view, which will give us a sense of the confusion that reigns in this subject: [https://CRAN.R-project.org/view=Spatial
](https://CRAN.R-project.org/view=Spatial).

One workshop cannot possibly teach you how to "do" spatial statistics, so the goal here today is to learn the basics and help to limit the information overload that might come from just cracking open the fire hose. When it comes to analyzing spatial data in R, you will hopefully learn where to look first and what R packages to reach for.


