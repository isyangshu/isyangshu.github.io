---
title: "Deformable Dynamic Sampling and Dynamic Predictable Mask Mining for Image Inpainting"
collection: publications
permalink: /publication/2023-10-26-paper-title-number-2
excerpt: 'Image Inpainting'
date: 2023-10-26
venue: 'TNNLS'
citation: Cai Shang, Yu Zeng, <strong>Shu Yang</strong>, Xu Jia, Huchuan Lu, You He
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10297120'
---

Existing state-of-the-art methods for surgical phase recognition either rely on the extraction of spatial-temporal features at short-range temporal resolution or adopt the sequential extraction of the spatial and temporal features across the entire temporal resolution. However, these methods have limitations in modeling spatial-temporal dependency and addressing spatial-temporal redundancy: 1) These methods fail to effectively model spatial-temporal dependency, due to the lack of long-range information or joint spatial-temporal modeling. 2) These methods utilize dense spatial features across the entire temporal resolution, resulting in significant spatial-temporal redundancy. In this paper, we propose the Surgical Transformer (Surgformer) to address the issues of spatial-temporal modeling and redundancy in an end-to-end manner, which employs divided spatial-temporal attention and takes a limited set of sparse frames as input. Moreover, we propose a novel Hierarchical Temporal Attention (HTA) to capture both global and local information within varied temporal resolutions from a target frame-centric perspective. Distinct from conventional temporal attention that primarily emphasizes dense long-range similarity, HTA not only captures long-term information but also considers local latent consistency among informative frames. HTA then employs pyramid feature aggregation to effectively utilize temporal information across diverse temporal resolutions, thereby enhancing the overall temporal representation. Extensive experiments on two challenging benchmark datasets verify that our proposed Surgformer performs favorably against the state-of-the-art methods. The code is released at https://github.com/isyangshu/Surgformer.
