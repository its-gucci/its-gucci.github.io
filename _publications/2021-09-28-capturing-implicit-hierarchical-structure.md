---
title: "Capturing implicit hierarchical structure in 3D biomedical images with self-supervised hyperbolic representations"
collection: publications
permalink: /publication/2021-09-28-capturing-implicit-hierarchical-structure
excerpt: 'Creating manual annotations for segementation, especially for high-resolution 3D image data, is expensive and time-consuming. We exploit the natural hierarchical organization of 3D biological data by using it as self-supervision to learn hyperbolic representations via a hyperbolic VAE, and use the learned representations to perform unsupervised 3D segmentation.'
date: 2021-09-28
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2021/file/291d43c696d8c3704cdbe0a72ade5f6c-Paper.pdf'
citation: 'Hsu, Joy, et al. "Capturing implicit hierarchical structure in 3D biomedical images with self-supervised hyperbolic representations." Advances in Neural Information Processing Systems 34 (2021): 5112-5123.'
---
![image](/files/hyp_pull_fig.png)

Abstract: We consider the task of representation learning for unsupervised segmentation of 3D voxel-grid biomedical images. We show that models that capture implicit hierarchical relationships between subvolumes are better suited for this task. To that end, we consider encoder-decoder architectures with a hyperbolic latent space, to explicitly capture hierarchical relationships present in subvolumes of the data. We propose utilizing a 3D hyperbolic variational autoencoder with a novel gyroplane convolutional layer to map from the embedding space back to 3D images. To capture these relationships, we introduce an essential self-supervised loss---in addition to the standard VAE loss---which infers approximate hierarchies and encourages implicitly related subvolumes to be mapped closer in the embedding space. We present experiments on synthetic datasets along with a dataset from the medical domain to validate our hypothesis. 

[[Download paper here](https://proceedings.neurips.cc/paper_files/paper/2021/file/291d43c696d8c3704cdbe0a72ade5f6c-Paper.pdf)][[Code](https://github.com/its-gucci/capturing-implicit-hierarchical-structure)]

Recommended citation: Hsu, Joy, et al. "Capturing implicit hierarchical structure in 3D biomedical images with self-supervised hyperbolic representations." Advances in Neural Information Processing Systems 34 (2021): 5112-5123.

A previous version of this paper was published as "Learning Hyperbolic Representations for Unsupervised 3D Segmentation".

