


# Deep Convolutional Generative Adversarial Network


Run in Google Colab

This project deal with images of fashion mnist dataset using a Deep Convolutional Generative Adversarial Network (DCGAN). The code is written using the Keras Sequential API.

What are GANs?
Generative Adversarial Networks (GANs) are one of the most interesting ideas in computer science today. Two models are trained simultaneously by an adversarial process. A generator ("the artist") learns to create images that look real, while a discriminator ("the art critic") learns to tell real images apart from fakes.


During training, the generator progressively becomes better at creating images that look real, while the discriminator becomes better at telling them apart. The process reaches equilibrium when the discriminator can no longer distinguish real images from fakes.



This notebook demonstrates this process on the Fashion MNIST dataset. The animation shows in notebook is a series of images produced by the generator as it was trained for 10 epochs. The images begin as random noise, and increasingly resemble fashion images over time.
