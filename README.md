# GAN
# Generative Adversarial Network for Handwritten Digit Synthesis

This project demonstrates the use of Generative Adversarial Networks (GANs) to generate synthetic handwritten digits that closely resemble the MNIST dataset. The generator and discriminator are both implemented using Convolutional Neural Networks (CNNs), showcasing advanced deep learning techniques.

## Key Features
1. Generator: Creates realistic handwritten digits starting from random noise vectors.
2. Discriminator: Distinguishes between real MNIST digits and synthetic ones, improving the generator iteratively.
3. Adversarial Training: Utilizes adversarial loss to train both models simultaneously, ensuring the generator becomes adept at fooling the discriminator.
4. Visualization: Includes functionality to save and display generated samples after each training epoch.

## How to Run
1. Clone the repository and open the project in Google Colab or a local environment.
2. Ensure TensorFlow and necessary dependencies are installed.
3. Set the Colab runtime to GPU for efficient training.
4. Execute the script to preprocess the MNIST dataset and begin training.
5. View the generated images, which are saved after every epoch.
