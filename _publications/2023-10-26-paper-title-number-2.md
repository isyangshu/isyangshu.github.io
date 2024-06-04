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

Existing image inpainting methods often produce artifacts that are caused by using vanilla convolution layers as building blocks that treat all image regions equally and generate holes at random locations with equal probability. This design does not differentiate the missing regions and valid regions in inference and does not consider the predictability of missing regions in training. To address these issues, we propose a deformable dynamic sampling (DDS) mechanism which is built on deformable convolutions (DCs), and a constraint is proposed to avoid the deformably sampled elements falling into the corrupted regions. Furthermore, to select both valid sample locations and suitable kernels dynamically, we equip DCs with content-aware dynamic kernel selection (DKS). In addition, to further encourage the DDS mechanism to find meaningful sampling locations, we propose to train the inpainting model with mined predictable regions as holes. During training, we jointly train a mask generator with the inpainting network to generate hole masks dynamically for each training sample. Thus, the mask generator can find large yet predictable missing regions as a better alternative to random masks. Extensive experiments demonstrate the advantages of our method over state-of-the-art methods qualitatively and quantitatively.
