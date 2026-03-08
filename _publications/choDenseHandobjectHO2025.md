---
title: "Dense hand-object (HO) GraspNet with full grasping taxonomy and dynamics"
collection: publications
permalink: /publication/choDenseHandobjectHO2025
excerpt: ''
date: 2024-09-01
venue: 'European Conference on Computer Vision (ECCV), 2024'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17'
imgurl: 'Pasted image 20260308212815.png'
authors:
  - name: Woojin Cho
    link: https://scholar.google.com/citations?hl=en&user=9QIim1QAAAAJ
  - name: Jihyun Lee
    link: https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17#auth-Jihyun-Lee
  - name: Minjae Yi
    link: https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17#auth-Minjae-Yi
  - name: Minje Kim
    link: https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17#auth-Minje-Kim
  - name: Taeyun Woo
    link: https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17#auth-Taeyun-Woo
  - name: Dongwhan Kim
    link: https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17#auth-Donghwan-Kim
  - name: Taewook Ha
    link: 
  - name: Hyokeun Lee
    link: https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17#auth-Hyokeun-Lee
  - name: Je-Hwan Ryu
    link: https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17#auth-Je_Hwan-Ryu
  - name: Woontack Woo
    link: https://scholar.google.com/citations?hl=en&user=s3Z4Q1oAAAAJ
  - name: Tae-Kyun Kim
    link: https://scholar.google.com/citations?hl=en&user=j2WcLecAAAAJ

links:
  - name: paper
    link: https://link.springer.com/chapter/10.1007/978-3-031-73007-8_17
  - name: project page
    link: https://hograspnet2024.github.io/
  - name: code
    link: https://github.com/kaist-uvr-lab/HOGraspNet
---

Existing datasets for 3D hand-object interaction are limited either in the data cardinality, data variations in interaction scenarios, or the quality of annotations. In this work, we present a comprehensive new training dataset for hand-object interaction called HOGraspNet. It is the only real dataset that captures full grasp taxonomies, providing grasp annotation and wide intraclass variations. Using grasp taxonomies as atomic actions, their space and time combinatorial can represent complex hand activities around objects. We select 22 rigid objects from the YCB dataset and 8 other compound objects using shape and size taxonomies, ensuring coverage of all hand grasp configurations. The dataset includes diverse hand shapes from 99 participants aged 10 to 74, continuous video frames, and a 1.5M RGB-Depth of sparse frames with annotations. It offers labels for 3D hand and object meshes, 3D keypoints, contact maps, and _grasp labels_. Accurate hand and object 3D meshes are obtained by fitting the hand parametric model (MANO) and the hand implicit function (HALO) to multi-view RGBD frames, with the MoCap system only for objects. Note that HALO fitting does not require any parameter tuning, enabling scalability to the dataset’s size with comparable accuracy to MANO. We evaluate HOGraspNet on relevant tasks: grasp classification and 3D hand pose estimation. The result shows performance variations based on grasp type and object class, indicating the potential importance of the interaction space captured by our dataset. The provided data aims at learning universal shape priors or foundation models for 3D hand-object interaction.