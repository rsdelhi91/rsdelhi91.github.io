---
title: "Probabilistic Distributed Intrusion Detection For Zero-Trust Multi-Access Edge Computing"
date: 2023-05-12T15:48:08+11:00
draft: true
featured_image: "/images/probcids.png"
tags: ["Research, MEC, Cybersecurity, 5G, CIDS, Zero Trust"]
---

This paper was published in IFIP NOMS 2023 and is available [here](https://ieeexplore.ieee.org/abstract/document/10154326)


The abstract of this paper is as follows:

With the advent of Multi-Access Edge Computing (MEC) in 5G, there is a shift in the core processing and deployment of applications to the edge of the network. This enables applications requiring ultra low latency response times and high bandwidth but also exposes them to new cyber attacks. One of the proposed ways to strengthen application security in MEC is to use Zero Trust Strategies (ZTS). However, despite its strong authentication and authorisation capabilities, it is still vulnerable to attacks and requires further mechanisms to detect anomalies, especially across multiple clusters. Collaborative Intrusion Detection Systems (CIDS) have been proposed for detecting sophisticated coordinated attacks but often fall short in detecting focused stealthy attacks. In this paper, we present a novel tree-based Probabilistic Distributed CIDS to detect stealthy and volumetric anomalies in service-to-service interactions deployed across multiple edge clusters with a Zero Trust Network setup. We perform our evaluation based on detection accuracy and network overhead and outline its performance improvement against a traditional Distributed CIDS and a previously proposed Hybrid CIDS. Based on an evaluation using telemetry data from real-world application clusters, our novel CIDS resulted in improvements in detection accuracy of 99.4% and network overhead of up to 51.81% when detecting anomalies in service path interactions, HTTP methods, service endpoint interactions, and unusual variance in numerical values comprising request size, response size, and traffic processing duration.