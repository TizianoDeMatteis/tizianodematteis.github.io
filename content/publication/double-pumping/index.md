---
title: "Temporal Vectorization: A Compiler Approach to Automatic Multi-Pumping"
date: 2022-10-01
publishDate: 2022-09-02T07:55:53.906943Z
authors: ["Carl-Johannes Johnsen", "Tiziano De Matteis Tal Ben-Nun", "Johannes de Fine Licht", "Torsten Hoefler"]
publication_types: ["1"]
abstract: " The multi-pumping resource sharing technique can overcome the limitations commonly found in single-clocked FPGA designs by allowing hardware components to operate at a higher clock frequency than the surrounding system. However, this optimization cannot be expressed in high levels of abstraction, such as HLS, requiring the use of hand-optimized RTL. In this paper we show how to leverage multiple clock domains for computational subdomains on reconfigurable devices through data movement analysis on high-level programs.  We offer a novel view on multi-pumping as a compiler optimization --- a superclass of traditional vectorization. As multiple data elements are fed and consumed, the computations are packed temporally rather than spatially. The optimization is applied automatically using an intermediate representation that maps high-level code to HLS. Internally, the optimization injects modules into the generated designs, incorporating RTL for fine-grained control over the clock domains. We obtain a reduction of resource consumption by up to 50% on critical components and 23% on average. For scalable designs, this can enable further parallelism, increasing overall performance. "
featured: false
publication: "*Proceedings of the International Conference on Computer-Aided Design (ICCAD22)*"
---
