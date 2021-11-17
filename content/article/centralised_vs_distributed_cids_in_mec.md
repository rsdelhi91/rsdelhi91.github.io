---
title: "Evaluation of Centralised vs Distributed Collaborative Intrusion Detection Systems in Multi-Access Edge Computing"
date: 2021-11-16T15:48:08+11:00
draft: true
featured_image: "/images/cids.png"
tags: ["Research, MEC, Cybersecurity, 5G, CIDS"]
---

This paper was published in IFIP Networking 2020 and is available [here](https://dl.ifip.org/db/conf/networking/networking2020/1570620127.pdf)


The abstract of this paper is as follows:

With the rapid adoption of next generation networking architectures in 5G, like Multi-Access Edge Computing (MEC), there is a shift in the core processing capabilities to the edge of the network. This helps facilitate higher bandwidth and ultra-low latency responses, but can increase the attack surface for cyber-attacks like Denial of Service (DoS) and Distributed Denial of Service (DDoS). To safeguard these architectures without degrading performance, we require mechanisms capable of detecting these attacks in near-real time. Collaborative Intrusion Detection Systems (CIDS) are a popular choice for detecting sophisticated coordinated attacks in large complex networks, and a prime candidate for use in this context. However, finding the right CIDS deployment model is not straightforward, with each model presenting its own set of challenges like accuracy as well as network and computational overhead. In this paper, we focus on evaluating two CIDS models - a centralised vs a distributed approach using Distributed Hash Tables (DHTs), based on their detection accuracy, CPU and memory usage, and data transmission overhead. We assess each approach through experimentation with a real-world worm dataset to understand the complexities involved in developing an efficient intrusion detection solution for MEC.