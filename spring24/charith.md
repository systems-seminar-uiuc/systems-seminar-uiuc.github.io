## Making compilers more evolvable with learned cost models

### Abstract

Compilers use cost models either implicitly or explicitly to make optimization and code generation decisions. Traditionally, these cost models are constructed manually as analytical models or are embedded into the compiler code directly. However, with the diversity and evolving nature of the workloads and hardware, manually maintaining such cost models is both cumbersome and error-prone. Such cost models easily become stale leading to poor optimization decisions. In this talk, I will show how we can automatically generate such cost models from data as opposed to manually writing them. Not only are these cost models significantly more accurate, but they are easier to develop and to maintain. I will demonstrate how to build data-driven cost models for different hardware (e.g. commodity hardware and domain-specific accelerators) as well as for different workloads (e.g. dense and sparse) that enable better code optimizations. As a testament to the success of this approach, Google has already deployed a learned cost model targeting TPUs, that not only enables better code generation, but also allows organic evolvability and adjustability with automatic periodic retrainings. Such evolvability is not possible in traditional analytical cost models.

### Speaker Bio

Charith Mendis is an Assistant Professor at the University of Illinois at Urbana-Champaign. Previously, he was a visiting faculty researcher at Google and was instrumental in designing and developing the learned TPU cost model used in production. His research interests are in automating compiler construction using both formal methods and machine learning techniques. He received his Ph.D. and Masters from the Massachusetts Institute of Technology and his B.Sc. from the University of Moratuwa. He recently co-led the DARPA ISAT study on “ML Optimized Compilers for Heterogeneous Architectures (MOCHA)”. He is the recipient of an NSF CAREER Award, an IEEE Micro Top Picks honorable mention, the William A. Martin outstanding masters thesis award at MIT, a best student paper award, a best paper award, and the university gold medal for his B.Sc. He has published work at both top programming languages venues such as PLDI and ASPLOS  as well as at top machine learning venues such as ICML and NeurIPS. 

 

