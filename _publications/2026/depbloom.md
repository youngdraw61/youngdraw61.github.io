---
title:          "DepBloom: A Dependency-Aware Framework for Multi-GPU Temporal Graph Neural Networks Training"
date:           2026-04-15 00:00:00 +0800
selected:       true
# pub:            "International Conference on Machine Learning (ICML)"
pub_pre:        "Submitted to ASPLOS'27"
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       ""
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  We propose DepBloom to accelerate multi-GPU TGNN training with three techniques (1) temporally bounded spatial partitioning to reduce unnecessary cross-GPU synchronization and improve parallelism; (2) intra-batch memory refinement to recover missing short-range temporal dependencies inside enlarged batches; (3) critical-path optimization to prioritize urgent memory updates while deferring non-critical work during multi-GPU pipeline execution. Experimental results across representative models and diverse datasets show that DepBloom reduces multi-GPU training latency by 2.63$\times$ on average and up to 5.16$\times$ compared to state-of-the-art methods, while maintaining comparable or better model accuracy.
cover:          /assets/images/paper/2026/depbloom.jpg
authors:
  - Yang Zhao
  - Yue Dai
  - Liang Qiao
  - et al.
links:
  Code: https://github.com/aflyingsheep/DepBloom
---
