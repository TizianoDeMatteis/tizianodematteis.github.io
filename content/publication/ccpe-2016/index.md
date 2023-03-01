---
title: "Continuous Skyline Queries on Multicore Architectures"
date: 2016-01-01
publishDate: 2021-02-18T14:22:23.882994Z
authors: ["Tiziano De Matteis", "Salvatore Di Girolamo", "Gabriele Mencagli"]
publication_types: ["2"]
abstract: "The emergence of real-time decision-making applications in domains like high-frequency trading, emergency management and service level analysis in communication networks, has led to the definition of new classes of queries. Skyline queries are a notable example. Their results consist of all the tuples whose attribute vector is not dominated (in the Pareto sense) by one of any other tuple. Because of their popularity, skyline queries have been studied in terms of both sequential algorithms and parallel implementations for multiprocessors and clusters. Within the Data Stream Processing paradigm, traditional database queries on static relations have been revised in order to operate on continuous data streams. Most of the past papers propose sequential algorithms for continuous skyline queries, whereas there exist very few works targeting implementations on parallel machines. This paper contributes to fill this gap by proposing a parallel implementation for multicore architectures. We propose: i) a parallelization of the eager algorithm based on the notion of Skyline Influence Time, ii) optimizations of the reduce phase and load-balancing strategies to achieve near-optimal speedup, iii) a set of experiments with both synthetic benchmarks and a real dataset in order to show our implementation effectiveness"
featured: false
publication: "*Concurrency and Computation: Practice and Experience*"
url_pdf: "http://dx.doi.org/10.1002/cpe.3866"
doi: "10.1002/cpe.3866"
---

