# New-Digit-PyTorch
Creating a new digit using Convolutional Autoencoder in PyTorch.

We implement the famous convolutional autoencoders using Pytorch to create a new digit or many such new digits. In the project, we train the Encoder and the Decoder both based on convolution and transposed convolution operations. The architecture is trained on the famous MNIST Handwritten dataset. After training the architecture with the condition that the input should be equal to the output, the Encoder is used to find the mean of all the digits. Then we take any two digits, take their weighted sum such that the weights add up to 1. We then pass on the mean vector to the decoder to get the output.
