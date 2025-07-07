---
title: "LiquidGEMM: Hardware-Efficient W4A8 GEMM for High-Performance LLM Serving."
collection: publications
category: conferences
permalink: /publication/2025-11-16-paper-LiquidGEMM-number-1
excerpt: 'This paper is about LiquidGEMM.'
date: 2025-11-16
venue: ' The International Conference for High Performance Computing, Networking, Storage, and Analysis (SC)'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

In this paper, we present LiquidGEMM, a hardware-efficient W4A8 GEMM kernel for efficient LLM serving. LiquidGEMM designs two key techniques: LiquidQuant, a hardware-efficient quantization method that enables fast, overflow-safe dequantization using just two arithmetic instructions per four elements; and an implicit fine-grained pipeline that fully overlaps weight loading, dequantization, and MMA across warp groups without software synchronization or redundant memory traffic. Experimental results show that LiquidGEMM achieves up to 2.90x speedup over state-of-the-art W4A8 kernels and up to 4.94x end-to-end system-level speedup.
