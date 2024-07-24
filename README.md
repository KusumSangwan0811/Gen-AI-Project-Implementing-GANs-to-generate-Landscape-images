# Landscape Image Generation Using Generative Adversarial Networks (GANs)

In this project, we generate landscape image by implimenting GANs on Landscape dataset. Generative Adversarial Networks (GANs) offer a unique approach to generative modeling, characterized by a competitive interplay between two neural networks: Generators and Discriminators. 


## Dataset Preparation
The dataset is prepared by downloading and preprocessing Pokémon images, which includes:

1. Resizing images
2. Center cropping
3. Converting images to tensors
4. Normalizing the data


## Model Architecture
* Generator: Defined using transpose convolutional layers to generate realistic images from random noise.
* Discriminator: Defined using convolutional layers to distinguish between real and fake images.


## Training Process
The training process involves alternating between:

1. Training the Discriminator: To distinguish between real and generated (fake) images.
2. Training the Generator: To produce more realistic images that can fool the discriminator.


## Visualization
The training progress is visualized through:

1. Loss and Score Plots: Showing the performance of both the generator and discriminator over time.
2. Generated Image Samples: Displaying the quality of images produced by the generator at different stages of training.
