---
title: "A Disentangled Recognition and Nonlinear Dynamics Model for Unsupervised Learning"
collection: publications
permalink: /publications/kvae
venue: "Advances in Neural Information Processing Systems 30 (NIPS 2017)"
excerpt: 'The Kalman variational auto-encoder is a framework for unsupervised learning of sequential data that disentangles two latent representations: an object’s representation, coming from a recognition model, and a latent state describing its dynamics. The recognition model is represented by a convolutional variational auto-encoder and the latent dynamics model as a linear Gaussian state space model (LGSSM).'
date: 2017-12-01
paperurl: http://papers.nips.cc/paper/6951-a-disentangled-recognition-and-nonlinear-dynamics-model-for-unsupervised-learning.pdf
citation: 'Marco Fraccaro, Simon Kamronn, Ulrich Paquet, Ole Winther, (2017). A Disentangled Recognition and Nonlinear Dynamics Model for Unsupervised Learning. <i>Advances in Neural Information Processing Systems 30</i>.'
---

## Abstract
This paper takes a step towards temporal reasoning in a dynamically changing video, not in the pixel space that constitutes its frames, but in a latent space that describes the non-linear dynamics of the objects in its world. We introduce the Kalman variational auto-encoder, a framework for unsupervised learning of sequential data that disentangles two latent representations: an object's representation, coming from a recognition model, and a latent state describing its dynamics. As a result, the evolution of the world can be imagined and missing data imputed, both without the need to generate high dimensional frames at each time step. The model is trained end-to-end on videos of a variety of simulated physical systems, and outperforms competing methods in generative and missing data imputation tasks.

See more at https://sites.google.com/view/kvae
