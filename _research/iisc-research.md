---
title: "Research Intern"
collection: research
type: "Hardware Research"
permalink: /research/iisc-research
venue: "Department of Supercomputer and Education Center, Indian Institute of Science"
date: 2019-05-01
location: "Bengaluru, India"
---

__Supervisor:__ Prof R. [Govindarajan](https://www.csa.iisc.ac.in/~govind/)

I worked on writing microbenchmarks for observing hardware behavior and potential optimizations such as prefetching between caches. The target architecture was Intel Haswell architecture and I successfully corroborated the sizes of the L1, L2, and L3 caches and the virtual page size on my personal computer. I also developed a simple microbenchmark that used a fine-grained strided access pattern in a large array to study the prefetching in both the Data and Instruction caches. I was able to understand and explain the functioning of the L1 IP prefetcher and the L2 Spacial prefetchers which prefetch data closer to the cache for faster access times. This corroborated Intel's public documents regarding the Haswell architecture. I used C++ and Intel intrinsics (specifically \_\_rdtsc and \_\_rdtscp instructions) to get fine-grained measurements of the hit/miss times for each cache. 
