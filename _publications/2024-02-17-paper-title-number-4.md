---
title: "MambaMIL: Enhancing Long Sequence Modeling with Sequence Reordering in Computational Pathology"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Cancer Subtyping/Survival Prediction'
date: 2024-02-17
venue: 'MICCAI (Early Accept)'
paperurl: 'https://arxiv.org/pdf/2403.06800'
citation: <strong>Shu Yang</strong>, <strong>Yihui Wang</strong>, Hao Chen
---

Multiple Instance Learning (MIL) has emerged as a dominant paradigm to extract discriminative feature representations within Whole Slide Images (WSIs) in computational pathology. Despite driving notable progress, existing MIL approaches suffer from limitations in facilitating comprehensive and efficient interactions among instances, as well as challenges related to time-consuming computations and overfitting. In this paper, we incorporate the Selective Scan Space State Sequential Model (Mamba) in Multiple Instance Learning (MIL) for long sequence modeling with linear complexity, termed as MambaMIL. By inheriting the capability of vanilla Mamba, MambaMIL demonstrates the ability to comprehensively understand and perceive long sequences of instances. Furthermore, we propose the Sequence Reordering Mamba (SR-Mamba) aware of the order and distribution of instances, which exploits the inherent valuable information embedded within the long sequences. With the SR-Mamba as the core component, MambaMIL can effectively capture more discriminative features and mitigate the challenges associated with overfitting and high computational overhead. Extensive experiments on two public challenging tasks across nine diverse datasets demonstrate that our proposed framework performs favorably against state-of-the-art MIL methods. The code is released at https://github.com/isyangshu/MambaMIL.
