---
title: "On dynamic memory allocation in sliding-window parallel patterns for streaming analytics"
date: 2017-09-01
publishDate: 2021-02-18T14:22:23.890856Z
authors: ["Massimo Torquati", "Gabriele Mencagli", "Maurizio Drocco", "Marco Aldinucci", "Tiziano De Matteis", "Marco Danelutto"]
publication_types: ["2"]
abstract: "This work studies the issues related to dynamic memory management in Data Stream Processing, an emerging paradigm enabling the real-time processing of live data streams. In this paper, we consider two streaming parallel patterns and we discuss different implementation variants related to how dynamic memory is managed. The results show that the standard mechanisms provided by modern C++ are not entirely adequate for maximizing the performance. Instead, the combined use of an efficient general purpose memory allocator, a custom allocator optimized for the pattern considered and a custom variant of the C++ shared pointer mechanism, provides a performance improvement up to 16% on the best case."
featured: false
publication: "*The Journal of Supercomputing*"
url_pdf: "https://doi.org/10.1007/s11227-017-2152-1"
doi: "10.1007/s11227-017-2152-1"
---

