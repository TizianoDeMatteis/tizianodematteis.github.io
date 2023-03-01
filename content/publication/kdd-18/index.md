---
title: "D2K: Scalable Community Detection in Massive Networks via Small-Diameter k-Plexes"
date: 2018-01-01
publishDate: 2021-02-18T14:22:23.878000Z
authors: ["Alessio Conte", "Tiziano De Matteis", "Daniele De Sensi", "Roberto Grossi", "Andrea Marino", "Luca Versari"]
publication_types: ["1"]
abstract: "This paper studies kplexes, a well known pseudo-clique model for network communities. In a kplex, each node can miss at most $k-1$ links. Our goal is to detect large communities in today's real-world graphs which can have hundreds of millions of edges. While many have tried, this task has been elusive so far due to its computationally challenging nature: kplexes and other pseudo-cliques are harder to find and more numerous than cliques, a well known hard problem. We present D2K, which is the first algorithm able to find large kplexes of very large graphs in just a few minutes. The good performance of our algorithm follows from a combination of graph-theoretical concepts, careful algorithm engineering and a high-performance implementation. In particular, we exploit the low degeneracy of real-world graphs, and the fact that large enough kplexes have diameter~2. We validate a sequential and a parallel/distributed implementation of D2K on real graphs with up to half a billion edges."
featured: true
publication: "*Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery &#38; Data Mining*"
tags: ["community discovery", "graph enumeration", "k-plexes", "parallel programming"]
url_pdf: "http://doi.acm.org/10.1145/3219819.3220093"
doi: "10.1145/3219819.3220093"
---

