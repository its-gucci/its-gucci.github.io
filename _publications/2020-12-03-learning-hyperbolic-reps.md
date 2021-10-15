---
title: "Learning Hyperbolic Representations for Unsupervised 3D Segmentation"
collection: publications
permalink: /publication/2020-12-03-learning-hyperbolic-reps
excerpt: 'Creating manual annotations for segementation, especially for high-resolution 3D image data, is expensive and time-consuming. We exploit the natural hierarchical organization of 3D biological data by using it as self-supervision to learn hyperbolic representations via a hyperbolic VAE, and use the learned representations to perform unsupervised 3D segmentation.'
date: 2020-12-03
venue: 'NeurIPS Differential Geometry Workshop (Top 5 paper)'
paperurl: 'https://arxiv.org/pdf/2012.01644.pdf'
citation: 'Gu, Jeffrey* and Hsu, Joy* and Yeung, Serena. (2020). &quot;Learning Hyperbolic Representations for Unsupervised 3D Segmentation.&quot; <i>arXiv</i>. arXiv:2012.01644.'
---
![image](/files/hyp_pull_fig.png)

Abstract: There exists a need for unsupervised 3D segmentation on complex volumetric data, particularly when annotation ability is limited or discovery of new categories is desired. Using the observation that much of 3D volumetric data is innately hierarchical, we propose learning effective representations of 3D patches for unsupervised segmentation through a variational autoencoder (VAE) with a hyperbolic latent space and a proposed gyroplane convolutional layer, which better models the underlying hierarchical structure within a 3D image. We also introduce a hierarchical triplet loss and multi-scale patch sampling scheme to embed relationships across varying levels of granularity. We demonstrate the effectiveness of our hyperbolic representations for unsupervised 3D segmentation on a hierarchical toy dataset, BraTS whole tumor dataset, and cryogenic electron microscopy data.

[Download paper here](https://drive.google.com/file/d/1tFQWg72zKmLCV0EOnIH9cqqp1F3OVa72/view)

Recommended citation: Gu, Jeffrey* and Hsu, Joy* and Yeung, Serena. (2020). "Learning Hyperbolic Representations for Unsupervised 3D Segmentation." <i>arXiv</i>. arXiv:2012.01644.
