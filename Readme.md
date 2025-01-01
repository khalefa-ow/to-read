# 

* The Holon Approach for Simultaneously Tuning Multiple Components in a Self-Driving Database Management System with Machine Learning via Synthesized Proto-Actions
  [link](https://www.pdl.cmu.edu/ftp/Database/p3373-zhang.pdf)   
  Existing machine learning (ML) approaches to automatically optimize database management systems (DBMSs) only target a single configuration space at a time (e.g., knobs, query hints, indexes).  Simultaneously tuning multiple configuration spaces is challenging due to the combined space’s complexity. Previous tuning methods work around this by sequentially tuning individual spaces with a pool of tuners. However, these approaches struggle to coordinate their tuners and get stuck in local optima. This paper presents the Proto-X framework that holistically tunes multiple configuration spaces. The key idea of Proto-X is to identify similarities across multiple spaces, encode them in a high-dimensional model, and then synthesize “proto-actions” to navigate the organized space for promising configurations. We evaluate Proto-X against state-of-the-art DBMS tuning frameworks on tuning PostgreSQL for analytical and transactional workloads. By reasoning about configuration spaces that are orders of magnitude more complex than other frameworks (both in terms of quantity and variety), Proto-X discovers configurations that improve PostgreSQL’s performance by up to 53% over the next best approach.

* Static search trees: 40x faster than binary search 
  [link](https://curiouscoding.nl/posts/static-search-tree/#code-snippet--find-linear)  
  Very interesting to read.
  
