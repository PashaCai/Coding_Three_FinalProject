# Coding_Three_FinalProject
Submission: Element 2: Final Project
URL for Video:https://ual.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=d368225b-4fc8-4abe-a7b6-b022012246a0&start=0

This is a TensorFlow-based deep learning project where my goal is to classify images on the CIFAR-10 dataset using a two-layer neural network (NN).

In this project I first imported the CIFAR-10 dataset and split it into a training set and a test set. Then, some sample images are shown along with the average images for each category. As the images in the CIFAR-10 dataset are in colour, I need to convert them to grey scale (single channel) first and also encode the labels in one-hot. The code then shows some sample images after the conversion.

For the construction of the neural network model I defined a two-layer neural network with 32*32 neurons in the input layer (corresponding to the size of the image), 512 neurons in the first hidden layer and 10 neurons in the output layer (corresponding to the 10 categories).

For simulated training and simulated evaluation I used a gradient descent optimiser with a learning rate set to 0.05. 128 samples were randomly selected at a time for batch training. 100 epochs are trained and the current cross-entropy loss is printed at the end of each epoch. Finally, the accuracy of the model is evaluated using a test set.

The main goal of this project is to classify images in the CIFAR-10 dataset using a simple two-layer neural network model. It is my introductory attempt to deep learning.
