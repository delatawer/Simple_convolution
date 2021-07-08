# Simple_convolution

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other.

![image](https://user-images.githubusercontent.com/85259381/124947542-88bc4500-dfd5-11eb-8dbc-9ead2ea56f5b.png)

Saha, S. (2020, 15 octubre). A Comprehensive Guide to Convolutional Neural Networks — the ELI5 way. Medium. https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53

On this case, I use a simple pass through the image to extract some characteristics (on this case vertical and horizontal lines) with the following filters:

![1](https://user-images.githubusercontent.com/85259381/124948881-b655be00-dfd6-11eb-9601-0d48be9e7741.png)

After we upload an image like this one:

![batman](https://user-images.githubusercontent.com/85259381/124949283-09c80c00-dfd7-11eb-9659-d0b71384b31d.jpg)

We get an output like this:

![bat](https://user-images.githubusercontent.com/85259381/124949320-12b8dd80-dfd7-11eb-9156-8b15b08fbaa4.jpg)
