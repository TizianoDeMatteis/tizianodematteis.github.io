---
title: "StencilFlow: Mapping Large Stencil Programs to Distributed Spatial Computing Systems"
date: 2021-01-01
publishDate: 2021-02-18T14:22:23.873835Z
authors: ["Johannes de Fine Licht", "Andreas Kuster", "Tiziano De Matteis", "Tal Ben-Nun", "Dominic Hofer", "Torsten Hoefler"]
publication_types: ["1"]
abstract: "Spatial computing devices have been shown to significantly accelerate stencil computations, but have so far relied on unrolling the iterative dimension of a single stencil operation to increase temporal locality. This work considers the general case of mapping directed acyclic graphs of heterogeneous stencil computations to spatial computing systems, assuming large input programs without an iterative component. StencilFlow maximizes temporal locality and ensures deadlock freedom in this setting, providing end-to-end analysis and mapping from a high-level program description to distributed hardware. We evaluate our generated architectures on a Stratix 10 FPGA testbed, yielding 1.31 TOp/s and 4.18 TOp/s on single-device and multi-device, respectively, demonstrating the highest performance recorded for stencil programs on FPGAs to date. We then leverage the framework to study a complex stencil program from a production weather simulation application. Our work enables productively targeting distributed spatial computing systems with large stencil programs, and offers insight into architecture characteristics required for their efficient execution in practice."
featured: false
publication: "*Proceedings of the 19th ACM/IEEE International Symposium on Code Generation and Optimization (CGO'21)*"
---

