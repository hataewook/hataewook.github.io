---
title: "Temporally enhanced graph convolutional network for hand tracking from an egocentric camera"
collection: publications
permalink: /publication/choTemporallyEnhancedGraph2024
excerpt: ''
date: 2024-08-01
venue: 'Springer Virtual Reality'
paperurl: 'https://doi.org/10.1007/s10055-024-01039-3'
imgurl: 'Pasted image 20260308211945.png'
authors:
  - name: Woojin Cho
    link: https://scholar.google.com/citations?hl=en&user=9QIim1QAAAAJ
  - name: Taewook Ha
    link: 
  - name: Ikbeom Jeon
    link: https://www.researchgate.net/profile/Ikbeom-Jeon
  - name: Jinwoo Jeon
    link: https://scholar.google.com/citations?hl=en&user=vQhd0ZcAAAAJ
  - name: Tae-Kyun Kim
    link: https://scholar.google.com/citations?hl=en&user=j2WcLecAAAAJ
  - name: Woontack Woo
    link: https://scholar.google.com/citations?hl=en&user=s3Z4Q1oAAAAJ
links:
  - name: paper
    link: https://link.springer.com/article/10.1007/s10055-024-01039-3
  - name: code
    link: https://github.com/UVR-WJCHO/TEGCN_on_Hololens2
---

We propose a robust 3D hand tracking system in various hand action environments, including hand-object interaction, which utilizes a single color image and a previous pose prediction as input. We observe that existing methods deterministically exploit temporal information in motion space, failing to address realistic diverse hand motions. Also, prior methods paid less attention to efficiency as well as robust performance, i.e., the balance issues between time and accuracy. The Temporally Enhanced Graph Convolutional Network (TE-GCN) utilizes a 2-stage framework to encode temporal information adaptively. The system establishes balance by adopting an adaptive GCN, which effectively learns the spatial dependency between hand mesh vertices. Furthermore, the system leverages the previous prediction by estimating the relevance across image features through the attention mechanism. The proposed method achieves state-of-the-art balanced performance on challenging benchmarks and demonstrates robust results on various hand motions in real scenes. Moreover, the hand tracking system is integrated into a recent HMD with an off-loading framework, achieving a real-time framerate while maintaining high performance. Our study improves the usability of a high-performance hand-tracking method, which can be generalized to other algorithms and contributes to the usage of HMD in everyday life.