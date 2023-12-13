# TFDSViT

# Task-Free Continual Generation and Representation Learning via Dynamic Expansionable Memory Cluster

>📋 This is the implementation of Task-Free Continual Generation and Representation Learning via Dynamic Expansionable Memory Cluster

>📋 Accepted by AAAI 2024

# Title : Task-Free Continual Generation and Representation Learning via Dynamic Expansionable Memory Cluster

# Paper link : 


# Abstract

Human brains can continually acquire and learn new skills and knowledge over time from a dynamically changing environment without forgetting previously learnt information. Such a capacity can selectively transfer some important and recently seen information to the persistent knowledge regions of the brain. Inspired by this intuition, we propose a new memory-based approach for image reconstruction and generation in continual learning, consisting of a temporary and evolving memory, with two different storage strategies, corresponding to the temporary and permanent memorisation. The temporary memory aims to preserve up-to-date information while the evolving memory can dynamically increase its capacity in order to preserve permanent knowledge. This is achieved by the proposed memory expansion mechanism that selectively transfers those data samples deemed as important from the temporary memory to new clusters defined within the evolved memory according to an information novelty criterion. Such a mechanism promotes the knowledge diversity among clusters in the evolved memory, resulting in capturing more diverse information using a compact memory capacity. Furthermore, we propose a two-step optimization strategy for training a Variational Autoencoder (VAE) to implement generation and representation learning tasks, which updates the generator and inference models separately using two optimisation paths. This approach leads to a better trade-off between generation and reconstruction performance. We show empirically and theoretically that the proposed approach can learn meaningful latent representations while generating diverse images from different domains.

# Environment

1. tensorflow 2.1.3
2. python 3.6.13

# Training and evaluation

>📋 Python xxx.py, the model will be automatically trained and then report the results after the training.

>📋 Different parameter settings of OCM would lead to different results and we also provide different settings used in our experiments.

# BibTex
>📋 If you use our code, please cite our paper as:



