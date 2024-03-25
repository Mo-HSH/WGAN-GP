# Wasserstein GAN With Gradient Penalty

This repository contains an implementation of the Wasserstein GAN with Gradient Penalty (WGAN-GP) applied to the Fashion MNIST dataset.

## Overview

The Wasserstein GAN with Gradient Penalty is a variation of the Generative Adversarial Network (GAN) that focuses on improving training stability and generating high-quality images. It introduces a gradient penalty term in the loss function to enforce the Lipschitz constraint on the discriminator.

In this implementation, we use the Fashion MNIST dataset, a collection of Zalando's article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example in this dataset is a 28x28 grayscale image, belonging to one of 10 class labels.

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.
