# Learning CNNs with MNIST and LeNet-5

I built this project as a first hands-on introduction to convolutional neural networks (CNNs). The goal was to understand how a CNN turns image pixels into a prediction by following the data through each layer.

## What I built

The [Jupyter notebook](mnist_lenet5.ipynb) uses PyTorch to classify handwritten digits from MNIST. I started by applying a single 5 × 5 filter to a digit and visualizing its response. I then implemented a small CNN inspired by LeNet-5 and traced how the tensor dimensions change through convolution, pooling, and the final classifier.

After training the model for three epochs, I plotted the learning curves and inspected the feature maps learned by the first convolutional layer. The run recorded in the notebook reached **97.6% validation accuracy** and **97.9% test accuracy**.

## Reference

Yann LeCun, Léon Bottou, Yoshua Bengio, and Patrick Haffner, 1998. [Gradient-Based Learning Applied to Document Recognition (PDF)](https://leon.bottou.org/publications/pdf/ieee-1998.pdf)
