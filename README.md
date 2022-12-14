# Handwritten-Samples-Reconstruction

Construct a vanilla adversarial autoencoder to generate synthetic handwritten samples. There should be one encoder, one decoder, and one discriminator network in it. Three layers will be present in both the encoder and decoder networks. The discriminator will function as a binary classifier between real and fake images, with one input being the latent variables of all the images generated by the encoder and another being a random number of real samples chosen from a gaussian distribution.

Common specifications need to be followed are mentioned below:

• Dataset: MNIST

• Batch Size: 64

• Epochs: 100

• Optimizer: Adam • Loss Functions: a.BCE b.SSIM c. MSE

• No of intermediate nodes: 1000

• Laten Dimension feature tensor shape: 2 • Activation Function: ReLU / Sigmoid (use appropriately where necessary)

• Network Layer Type: Linear

• No of intermediate nodes in discriminator: 500 • Auto encoder network LR: 0.0001 • Discriminator network LR: 0.00005

** TASKS to be done **

1: Plot a sample of generated image and real image for all 0-9 digits.

2: Plot the reconstruction loss and discriminator loss over all the epochs in one graph. Comments on the nature/trend of the graphs produced. 

3: Write the entire training process of the vanilla adversarial autoencoder in brief and con-cise 3-5 step algorithm. 

4: Plot the training accuracy and loss values for all the 3 loss functions as 2 separate plots. 

5: Based on the plots in Q4, provide your comments on which of the suggested loss func-tions is best for the current task and why?
