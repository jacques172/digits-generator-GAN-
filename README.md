# number-generator-GAN-

Build and train a GAN that can generate hand-written images of digits (0-9).
- Used the MNIST dataset to train the model 76000 times with Pytorch framework
- Got a loss of 1.56 for the generator and 0.39 for the discriminator
- Generate batch of images for efficiency
- Used Bacth normalization in the generator for stability and the Leaky RELU in the discriminator to prevent the "dying RELU" problem
- Build a Deep Convolutional GAN(DCGAN) to improve the accuracy
- Solve the stability issues of DCGANs by building WGAN-GP 
- Made a conditional GAN in order to generate hand-written images of digits, conditioned on the digit to be generated
