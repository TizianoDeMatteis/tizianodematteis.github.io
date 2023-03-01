---
title: "Reducing Message Latency and CPU Utilization in the CAF Actor Framework"
date: 2018-01-01
publishDate: 2021-02-18T14:22:23.878937Z
authors: ["Massimo Torquati", "Tullio Menga", "Tiziano De Matteis", "Daniele De Sensi", "Gabriele Mencagli"]
publication_types: ["1"]
abstract: "In this work, we consider the C++ Actor Framework (CAF), a recent proposal that revamped the interest in building concurrent and distributed applications using the actor programming model in C++. CAF has been optimized for high-throughput computing, whereas message latency between actors is greatly influenced by the message data rate: at low and moderate rates the latency is higher than at high data rates. To this end, we propose a modification of the polling strategies in the work-stealing CAF scheduler, which can reduce message latency at low and moderate data rates up to two orders of magnitude without compromising the overall throughput and message latency at maximum pressure. The technique proposed uses a lightweight event notification protocol that is general enough to be used used to optimize the runtime of other frameworks experiencing similar issues."
featured: false
publication: "*Proceedings of the 26th Euromicro International Conference on Parallel, Distributed, and Network-Based Processing, PDP 2018*"
---

