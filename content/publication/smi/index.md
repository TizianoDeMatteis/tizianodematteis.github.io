---
title: "Streaming Message Interface: High-Performance DistributedMemory Programming on Reconfigurable Hardware"
date: 2019-11-01
publishDate: 2021-02-18T14:22:23.876127Z
authors: ["Tiziano De Matteis", "Johannes de Fine Licht", "Jakub Beránek", "Torsten Hoefler"]
publication_types: ["1"]
abstract: "Distributed memory programming is the established paradigm used in high-performance computing (HPC) systems, requiring explicit communication between nodes and devices. When FPGAs are deployed in distributed settings, communication is typically handled either by going through the host machine, sacrificing performance, or by streaming across fixed device-to-device connections, sacrificing flexibility. We present Streaming~Message~Interface~(SMI), a communication model and API that unifies explicit message passing with a hardware-oriented programming model, facilitating minimal-overhead, flexible, and productive inter-FPGA communication. Instead of bulk transmission, messages are streamed across the network during computation, allowing communication to be seamlessly integrated into pipelined designs. We present a high-level synthesis implementation of SMI targeting a dedicated FPGA interconnect, exposing runtime-configurable routing with support for arbitrary network topologies, and implement a set of distributed memory benchmarks. Using SMI, programmers can implement distributed, scalable HPC programs on reconfigurable hardware, without deviating from best practices for hardware design."
featured: true
publication: "*Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC19)*"
url_pdf: "https://doi.org/10.1145/3295500.3356201"
doi: "10.1145/3295500.3356201"
---
