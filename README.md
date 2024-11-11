# Monet-Image-Replication-DCGAN

The aim of this project is to create a generative deep learning model that can successfully produce semi-realistic faux Calude Monet paintings. Specifically, a Generative Adversarial Network (GAN) is created to produce these faux paintings. A GAN is a combination of two neural networks that are called generator and discriminator. The generator is the neural network that produces the faux paintings. Before training, the GAN is only able to produce a noise output. The GAN is trained using feedback from the discriminator, whose job is to be able to recognize the difference between a faux painting and a real Monet painting. These two networks are oppossed to each other - the generator tries to trick the discriminator into thinking its generated images are real and the discriminator works to ensure it can tell the difference between the real and fake images.

For this project, the task is to build a GAN that generates 7,500 Monet-style images.

The data for this project can be found here:
https://www.kaggle.com/competitions/gan-getting-started/data
