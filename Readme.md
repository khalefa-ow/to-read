# Random Pointers

I would gather random interesting links and papers.


* The Holon Approach for Simultaneously Tuning Multiple Components in a Self-Driving Database Management System with Machine Learning via Synthesized Proto-Actions   
  [link](https://www.pdl.cmu.edu/ftp/Database/p3373-zhang.pdf)   
  Existing machine learning (ML) approaches to automatically optimize database management systems (DBMSs) only target a single configuration space at a time (e.g., knobs, query hints, indexes).  Simultaneously tuning multiple configuration spaces is challenging due to the combined space’s complexity. Previous tuning methods work around this by sequentially tuning individual spaces with a pool of tuners. However, these approaches struggle to coordinate their tuners and get stuck in local optima. This paper presents the Proto-X framework that holistically tunes multiple configuration spaces. The key idea of Proto-X is to identify similarities across multiple spaces, encode them in a high-dimensional model, and then synthesize “proto-actions” to navigate the organized space for promising configurations. We evaluate Proto-X against state-of-the-art DBMS tuning frameworks on tuning PostgreSQL for analytical and transactional workloads. By reasoning about configuration spaces that are orders of magnitude more complex than other frameworks (both in terms of quantity and variety), Proto-X discovers configurations that improve PostgreSQL’s performance by up to 53% over the next best approach.

* Static search trees: 40x faster than binary search   
  [link](https://curiouscoding.nl/posts/static-search-tree/#code-snippet--find-linear)  
  Very interesting to read.
  
* A Critique of Modern SQL And A Proposal Towards A Simple and Expressive Query Language  
  [link](https://www.cidrdb.org/cidr2024/papers/p48-neumann.pdf)  
  The first contribution of the paper is a comprehensive critique of modern SQL, informed by an analysis of real-world SQL queries. This provides the motivation for our second contribution: the Simple ANd Expressive Query Language (SaneQL). SaneQL features a straightforward and consistent syntax, which improves its learnability and ease of implementation. Additionally, it provides extensibility, with the added ability to define new operators that integrate seamlessly with the existing built-in ones. Unlike most data frame APIs and NoSQL query languages, SaneQL fully embraces the core principles behind SQL, especially multiset semantics. We propose that adopting SaneQL’s approach can ensure the enduring success of relational database technology, offering the power of SQL’s underlying concepts through a more accessible and flexible language.  

* Adaptive Execution of Compiled Queries  
  [link](https://db.in.tum.de/~leis/papers/adaptiveexecution.pdf)
  —Compiling queries to machine code is a very efficient way for executing queries. One often overlooked problem with compilation is the time it takes to generate machine code. Even with fast compilation frameworks like LLVM, generating machine code for complex queries often takes hundreds of milliseconds. Such durations can be a major disadvantage for workloads that execute many complex, but quick queries. To solve this problem, we propose an adaptive execution framework, which dynamically switches from interpretation to compilation. We also propose a fast bytecode interpreter for LLVM, which can execute queries without costly translation to machine code and dramatically reduces the query latency. Adaptive execution is fine-grained, and can execute code paths of the same query using different execution modes. Our evaluation shows that this approach achieves optimal performance in a wide variety of settings—low latency for smal.

* The Technology behind CedarDB    
    [link](https://cedardb.com/docs/technology/)

* Introducing DBRX: A New State-of-the-Art Open LLM    
    [link](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm)

* The Part of PostgreSQL We Hate the Most  
     [link](https://www.cs.cmu.edu/~pavlo/blog/2023/04/the-part-of-postgresql-we-hate-the-most.html)

 * Databases in 2024: A Year in Review  
    [link](https://www.cs.cmu.edu/~pavlo/blog/2025/01/2024-databases-retrospective.html)

* mooncake  
  [link](https://mooncake.dev/blog/how-we-built-pgmooncake)  
  [link](https://github.com/Mooncake-Labs/pg_mooncake)  

fifty shades of concurrency
It does not need to be black or white
can this would be done with LLM or code generations
https://www.youtube.com/watch?v=Mc3tTRkjCvE&ab_channel=StrangeLoopConference 
https://www.vldb.org/pvldb/vol16/p856-power.pdf
