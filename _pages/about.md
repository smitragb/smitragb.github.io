---
permalink: /
title: "Hey there! I'm Shashwatha! Welcome to my page!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I recently graduated from the University of Wisconsin-Madison (on Badgers!) with a Master's degree!

My research interests lie in the intersection of Mathematics and Computer Science. I am broadly interested in Algorithms, Theoretical Computer Science, Computational Complexity, and Cryptography. My Master's in Science at UW focused heavily on these topics, with my Research thesis on "Classical Verification for QMA". I did my Bachelor's at one of India's premier institutes: National Institute of Technology Karnataka.

Currently, I am learning the Rust programming language, and as a true Rustacean, I'm attempting to rewrite some of my academic projects in Rust. 

Work Experience
======
Right out of my Bachelor's, I got the opportunity to work with Oracle's Data team in San Francisco, USA. I collaborated remotely (during Covid) from Bengaluru, and contributed to Oracle's __In-Memory Expressions__ stack with critical enhancements and bug fixes. I am particularly proud of my contribution in improving the performance of _DATE/TIMESTAMP_ based queries by *6x* and a minimal space overhead. With this team, I got to work on Oracle's columnar memory formats and the full database internals from close quarters! My work was presented at Oracle CloudWorld in 2022 as well! I'm extremely grateful to my managers: [Agnivo Saha](https://www.linkedin.com/in/agnivo-saha-88990099/) and [Aurosish Mishra](https://www.linkedin.com/in/agnivo-saha-88990099/) for their valuable feedback.

A few projects I'm proud of!
------
- *Batching Lattice-based Zero-Knowledge proofs for Integer Relations*: [IRELZK](https://github.com/Shashwatha-Mitra/bat-lns)

This project was my foray into Lattice-based constructions for ZK proofs and my attempt to improve the current state of the art. The main idea of this project is rather cute: use randomized aggregation of the individual proof elements to get a single proof for a batch of instances. The idea provably retains the security of the protocol. 
- *Implementing Hermes Replication for a durable KV-store*: [Hermes](https://github.com/Shashwatha-Mitra/hermes-kvs)

This project was a part of my Distributed Systems course at UW. We set out to implement the Hermes [replication protocol](https://hermes-protocol.com/) for a durable KV-store built using sqlite3. We compared this with our implementation of a sharded Chain Replication (CR) protocol for completeness, with Hermes beating CR by *4x* on writes. (Rust version coming soon! xD)
- *Simulating Young's Double slit Experiment for a Particle-in-a-box*: [Double-slit](https://github.com/Shashwatha-Mitra/double-slit-expt)

This project was a part of my Computational Mathematics course at UW. I always wanted to see the fringe pattern emerge from the solution to the Schrodinger equation and numerical simulations. With various methods like Finite-Difference, Alternating Direction Implicit schemes, and Spectral methods, I reproduced the fringe pattern observed by the Young's double slit experiment in both a finite and infinite potential barrier case; essentially showing how quantum tunneling occurs when electrons are confined in a finite potential well!
