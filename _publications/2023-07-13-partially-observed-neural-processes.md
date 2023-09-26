---
title: "Generalizable Neural Fields as Partially Observed Neural Processes"
collection: publications
permalink: /publication/2023-07-13-partially-observed-neural-processes
excerpt: 'Neural processes outperform gradient-based meta-learning and other methods for neural field generalization'
date: 2023-07-13
venue: 'International Conference on Computer Vision (ICCV)'
paperurl: 'https://arxiv.org/pdf/2309.06660.pdf'
citation: 'Gu, Jeffrey, Kuan-Chieh Wang, and Serena Yeung. "Generalizable Neural Fields as Partially Observed Neural Processes." arXiv preprint arXiv:2309.06660 (2023).'
---

Abstract: Neural fields, which represent signals as a function parameterized by a neural network, are a promising alternative to traditional discrete vector or grid-based representations. Compared to discrete representations, neural representations both scale well with increasing resolution, are continuous, and can be many-times differentiable. However, given a dataset of signals that we would like to represent, having to optimize a separate neural field for each signal is inefficient, and cannot capitalize on shared information or structures among signals. Existing generalization methods view this as a meta-learning problem and employ gradient-based meta-learning to learn an initialization which is then fine-tuned with test-time optimization, or learn hypernetworks to produce the weights of a neural field. We instead propose a new paradigm that views the large-scale training of neural representations as a part of a partially-observed neural process framework, and leverage neural process algorithms to solve this task. We demonstrate that this approach outperforms both state-of-the-art gradient-based meta-learning approaches and hypernetwork approaches.

[Project Page](https://its-gucci.github.io/ponp/)[Download paper here](https://arxiv.org/pdf/2309.06660.pdf)

Recommended citation: Gu, Jeffrey, Kuan-Chieh Wang, and Serena Yeung. "Generalizable Neural Fields as Partially Observed Neural Processes." arXiv preprint arXiv:2309.06660 (2023).
