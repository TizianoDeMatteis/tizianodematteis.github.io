---
title: "Parallel Patterns for Window-Based Stateful Operators on Data Streams: An Algorithmic Skeleton Approach"
date: 2017-04-01
publishDate: 2021-02-18T14:22:23.883446Z
authors: ["Tiziano De Matteis", "Gabriele Mencagli"]
publication_types: ["2"]
abstract: "The topic of Data Stream Processing is a recent and highly active research area dealing with the in-memory, tuple-by-tuple analysis of streaming data. Continuous queries typically consume huge volumes of data received at a great velocity. Solutions that persistently store all the input tuples and then perform off-line computation are impractical. Rather, queries must be executed continuously as data cross the streams. The goal of this paper is to present parallel patterns for window-based stateful operators, which are the most representative class of stateful data stream operators. Parallel patterns are presented ``à la'' Algorithmic Skeleton, by explaining the rationale of each pattern, the preconditions to safely apply it, and the outcome in terms of throughput, latency and memory consumption. The patterns have been implemented in the $$backslashmathtt FastFlow$$ FastFlow framework targeting off-the-shelf multicores. To the best of our knowledge this is the first time that a similar effort to merge the Data Stream Processing domain and the field of Structured Parallelism has been made."
featured: false
publication: "*International Journal of Parallel Programming*"
url_pdf: "https://doi.org/10.1007/s10766-016-0413-x"
doi: "10.1007/s10766-016-0413-x"
---

