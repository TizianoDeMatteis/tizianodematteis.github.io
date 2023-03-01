---
title: FBLAS
summary: BLAS implementation for Intel FPGA
tags:
- FPGA
date: "2019-03-01"
show_date: false


# Optional external URL for project (replaces project detail page).
#external_link: "https://github.com/spcl/FBLAS"

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


**FBLAS** is a porting of the BLAS numerical library ([http://www.netlib.org/blas/](http://www.netlib.org/blas/)) for Intel FPGA platform. 


FBLAS provides two layers of abstraction: 

* **HLS modules**, which can be integrated into existing hardware designs. They implement BLAS routines (`DOT`, `GEMV`, `GEMM`, etc.). Modules have been designed with compute performance in mind, exploiting the spatial parallelism and fast on-chip memory on FPGAs and have a streaming interface: data is received and produced using channels. In this way, they can be composed and communicate using on-chip resources rather than off-chip device RAM;

* a high-level **Host API** conforming to the classical BLAS interface that allows the user to invoke routines directly from a host program. No prior knowledge on FPGA architecture and/or tools is needed. The user writes a standard OpenCL program: she is responsible to transferring data to and from
the device, she can invoke the desired FBLAS routines working on the FPGA memory, and then she copies back the result from the device.

For further information on how to use the library, please refer to the [project page](https://github.com/spcl/FBLAS/).
