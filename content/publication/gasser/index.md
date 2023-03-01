---
title: "GASSER: An Auto-Tunable System for General Sliding-Window Streaming Operators on GPUs"
date: 2019-04-01
publishDate: 2021-02-18T14:22:23.876758Z
authors: ["Tiziano De Matteis", "Gabriele Mencagli", "Daniele De Sensi", "Massimo Torquati", "Marco Danelutto"]
publication_types: ["2"]
abstract: "Today's stream processing systems handle high-volume data streams in an efficient manner. To achieve this goal, they are designed to scale out on large clusters of commodity machines. However, despite the efficient use of distributed architectures, they lack support to co-processors like graphical processing units (GPUs) ready to accelerate data-parallel tasks. The main reason for this lack of integration is that GPU processing and the streaming paradigm have different processing models, with GPUs needing a bulk of data present at once while the streaming paradigm advocates a tuple-at-a-time processing model. This paper contributes to fill this gap by proposing Gasser, a system for offloading the execution of sliding-window operators on GPUs. The system focuses on completely general functions by targeting the parallel processing of non-incremental queries that are not supported by the few existing GPU-based streaming prototypes. Furthermore, Gasser provides an auto-tuning approach able to automatically find the optimal value of the configuration parameters (i.e., batch length and the degree of parallelism) needed to optimize throughput and latency with the given query and data stream. The experimental part assesses the performance efficiency of Gasser by comparing its peak throughput and latency against Apache Flink, a popular and scalable streaming system. Furthermore, we evaluate the penalty induced by supporting completely general queries against the performance achieved by the state-of-the-art solution specifically optimized for incremental queries. Finally, we show the speed and accuracy of the auto-tuning approach adopted by Gasser, which is able to self-configure the system by finding the right configuration parameters without manual tuning by the users."
featured: False
publication: "*IEEE Access*"
doi: "10.1109/ACCESS.2019.2910312"
---

