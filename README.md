# What are GANs?

[Generative Adversarial Networks](https://arxiv.org/abs/1406.2661) (GANs) are one of the most interesting ideas in computer science today. This repository demonstrates the training process of a Deep Convolutional GAN (DCGAN) to generate images based on the MNIST dataset.

## Overview

In this project, two models are trained simultaneously by an adversarial process:  
- **Generator**: Learns to create images that resemble real data.  
- **Discriminator**: Learns to distinguish between real and fake images.

During training:
1. The generator becomes progressively better at producing realistic images.
2. The discriminator improves in identifying fake images until equilibrium is reached.

![GAN Training Process](https://github.com/tensorflow/docs/blob/master/site/en/tutorials/generative/images/gan2.png?raw=1)

This repository also includes animations showing how the generator produces increasingly realistic images over time.
