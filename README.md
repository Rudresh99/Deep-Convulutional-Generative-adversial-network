# Deep-Convulutional-Generative-adversial-network

Sign in
TensorFlow Core

TensorFlow
TensorFlow
Learn
TensorFlow Core
Tutorials
Deep Convolutional Generative Adversarial Network


Run in Google Colab
View source on GitHub
Download notebook
This tutorial dee images of handwritten digits using a Deep Convolutional Generative Adversarial Network (DCGAN). The code is written using the Keras Sequential API with a tf.GradientTape training loop.

What are GANs?
Generative Adversarial Networks (GANs) are one of the most interesting ideas in computer science today. Two models are trained simultaneously by an adversarial process. A generator ("the artist") learns to create images that look real, while a discriminator ("the art critic") learns to tell real images apart from fakes.

A diagram of a generator and discriminator

During training, the generator progressively becomes better at creating images that look real, while the discriminator becomes better at telling them apart. The process reaches equilibrium when the discriminator can no longer distinguish real images from fakes.

A second diagram of a generator and discriminator

This notebook demonstrates this process on the MNIST dataset. The following animation shows a series of images produced by the generator as it was trained for 50 epochs. The images begin as random noise, and increasingly resemble hand written digits over time.
