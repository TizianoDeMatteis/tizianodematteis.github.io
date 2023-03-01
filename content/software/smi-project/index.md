---
title: SMI
summary: "Streaming Message Interface: High-Performance Distributed Memory Programming on Reconfigurable Hardware"
tags:
- FPGA
date: "2019-08-01"

# Optional external URL for project (replaces project detail page).
#external_link: "https://github.com/spcl/SMI"

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
<!-- <img align="left" width="128" height="128" src="/img/fblas_logo.png">/-->



**Streaming Message Interface** is a a distributed memory HLS programming model for **FPGAs** that provides
the convenience of message passing for HLS-programmed hardware devices. Instead of bulk transmission, typical of message passing model, 
with SMI messages are **streamed** across the network during computation, allowing communication to be seamlessly integrated into pipelined designs.

This repository contains an high-level synthesis implementation of SMI targeting OpenCL and Intel FPGAs, and all the 
applications used for the evaluation perfomed in the paper: *"Streaming Message Interface: High-Performance Distributed Memory
Programming on Reconfigurable Hardware"*, Tiziano De Matteis, Johannes de Fine Licht, Jakub Beránek, and Torsten Hofler. To appear in Proceedings of the International Conference for High Performance Computing, Networking, Storage, and Analysis, 2019 (SC 2019).


Please refer to the [project webpage](https://github.com/spcl/SMI/) and to the paper for a reference on how to use SMI for your own distributed FPGA programs.
