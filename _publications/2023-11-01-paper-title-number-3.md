---
title: "Real-Time Semantic Segmentation via a Densely Aggregated Bilateral Network"
collection: publications
permalink: /publication/2023-11-01-paper-title-number-3
excerpt: 'Semantic Segmentation'
date: 2023-11-01
venue: 'TNNLS'
citation: <strong>Shu Yang</strong>, Lu Zhang, Shuai Liu, Huchuan Lu, Hao Chen
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10304285'
---

With the growing demands of applications on online devices, the speed-accuracy trade-off is critical in the semantic segmentation system. Recently, the bilateral segmentation network has shown promising capacity to achieve the balance between favorable accuracy and fast speed, and has become the mainstream backbone in real-time semantic segmentation. Segmentation of target objects relies on high-level semantics, whereas it requires detailed low-level features to model specific local patterns for accurate location. However, the lightweight backbone of bilateral architecture limits the extraction of semantic context and spatial details. And the late fusion of the bilateral streams incurs the insufficient aggregation of semantic context and spatial details. In this article, we propose a densely aggregated bilateral network (DAB-Net) for real-time semantic segmentation. In the context path, a patchwise context enhancement (PCE) module is proposed to efficiently capture the local semantic contextual information from spatialwise and channelwise, respectively. Meanwhile, a context-guided spatial path (CGSP) is designed to exploit more spatial information by encoding finer details from the raw image and the transition from the context path. Finally, with multiple interactions between bilateral branches, the intertwined outputs from bilateral streams are combined in a unified decoder for a final interaction to further enhance the feature representation, which generates the final segmentation prediction. Experimental results on three public benchmarks demonstrate that our proposed method achieves higher accuracy with a limited decay in speed, which performs favorably against state-of-the-art real-time approaches and runs at 31.1 frames/s (FPS) on the high resolution. The source code is released at https://github.com/isyangshu/DABNet.
