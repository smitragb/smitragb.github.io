---
title: "Graduate Research Assistant"
collection: research
type: "Quantum Cryptography and Lattice-Based ZKPoK systems"
permalink: /research/uw-research
venue: "University of Wisconsin-Madison, Department of Computer Science"
date: 2024-02-01
location: "Madison, USA"
---

__Supervisor__: Prof. [Rishab Goyal](https://pages.cs.wisc.edu/~rishab/)

I worked on improving the current state of the art for Quantum-classical proof systems by using constructions such as Somewhere Extractable BARGs and Montone policy SNARGs for batched languages. I studied and extended Lattice-based Zero-Knowledge proof of Knowledge protocols with a polynomial commitment scheme. These can be used in developing post-quantum secure smart-contracts.

Classical Verification of Quantum Computing
===
Like NP, QMA is a class of languages which have an efficient verification algorithm given a valid quantum proof state. [Fitzsimons et al.](https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.120.040501?casa_token=zQY2EnAX6-IAAAAA%3AomkFeP47-SYTjTm8VPlfPHQAvcHO2rbB8GP_y2-Hk0gBa9u-LHFWdMcZj9YcAiBe52Afl3rOGWrDbgw) showed that a limited quantum computer is sufficient to validate the quantum state provided by an all-powerful prover. A simple combination with Urmila Mahadev's work (dubbed the [Mahadev protocol](https://arxiv.org/abs/1804.01082)) gives us the ability to verify the quantum computations using a classical computer! My work builds on this observation and [similar works](https://eprint.iacr.org/2022/857) to develop a 4-round protocol for verifying QMA instances, thus paving way to future where Quantum-Classical cloud workloads become a norm. 

Lattice-based ZKPoK protocols
===
I also studied the emerging field of post-quantum secure constructions for Commitment schemes and Zero-knowledge protocols. My exploration started with the impeccable thesis by [Gregor Seiler](https://scholar.google.com/citations?hl=en&user=o-mGsLkAAAAJ) and the [BDLOP](http://eprint.iacr.org/2016/997) commitment scheme. I also had a small [project](https://github.com/Shashwatha-Mitra/bat-lns) on improving the [LNS20](https://eprint.iacr.org/2020/1183) by batching the proof system and aggregating the proofs generated in each individual batches. The techniques used for this project are presented in subsequent works such as [LaBRADOR](https://eprint.iacr.org/2022/1341) which are essentially SNARKs using Module-LWE. 

