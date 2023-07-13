# Coding_Three_FinalProject
<h2>Submission: Element 2: Final Project</h2>
<p>URL for Video:https://ual.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=d368225b-4fc8-4abe-a7b6-b022012246a0&start=0</p>
<p>URL for The CIFAR-10 dataset:https://www.cs.toronto.edu/~kriz/cifar.html</p>
<hr>
This is a TensorFlow-based deep learning project where my goal is to classify images on the CIFAR-10 dataset using a two-layer neural network (NN).

In this project I first imported the CIFAR-10 dataset and split it into a training set and a test set. Then, some sample images are shown along with the average images for each category. As the images in the CIFAR-10 dataset are in colour, I need to convert them to grey scale (single channel) first and also encode the labels in one-hot. The code then shows some sample images after the conversion.

For the construction of the neural network model I defined a two-layer neural network with 32*32 neurons in the input layer (corresponding to the size of the image), 512 neurons in the first hidden layer and 10 neurons in the output layer (corresponding to the 10 categories).

For simulated training and simulated evaluation I used a gradient descent optimiser with a learning rate set to 0.05. 128 samples were randomly selected at a time for batch training. 100 epochs are trained and the current cross-entropy loss is printed at the end of each epoch. Finally, the accuracy of the model is evaluated using a test set.

The main goal of this project is to classify images in the CIFAR-10 dataset using a simple two-layer neural network model. It is my introductory attempt to deep learning.

In this project, the evaluation process is performed after the completion of model training. The evaluation uses the test set of the CIFAR-10 dataset, which includes 10,000 samples. During the training phase, I used the cross-entropy loss function as the optimization objective, and tracked the learning progress of the model by printing the loss value after each training epoch.

In the evaluation phase, I calculated the prediction accuracy of the model by comparing the predicted categories of test set samples by the model with the actual categories of the samples. Accuracy is defined as the proportion of samples correctly predicted to the total number of samples. The code finally outputs the prediction accuracy on the test set, which is the evaluation result.

In terms of using third-party resources, this project mainly uses the TensorFlow deep learning framework to construct and train the neural network model, and uses Matplotlib to display data and results. In addition, I used the cifar10.load_data() function provided by Keras to load the CIFAR-10 dataset.
<h2>Reference List</h2>
<h3></h3>Third-party etymologies:</h3>
TensorFlow, Keras, NumPy, Matplotlib.

<h3>The specific procedure refers to these resources:</h3>
<p>1. TensorFlow official documentation and tutorial: https://www.tensorflow.org/overview/</p>
<p>2. Keras official documentation and tutorials: https://keras.io/</p>
<p>3. NumPy official documentation and tutorial: https://numpy.org/doc/</p>
<p>4.Matplotlib official documents and tutorials: https://matplotlib.org/</p>

<h3>I also refer to the following tutorials on using TensorFlow to classify the cifar10 dataset:</h3>
1.TensorFlow official tutorial - CIFAR-10 classification: https://www.tensorflow.org/tutorials/images/cnn

2.The official Keras tutorial - CIFAR-10 classification: https://keras.io/examples/cifar10_cnn/

3.Image Classification with Convolutional Neural Networks: https://medium.com/@ksusorokina/image-classification-with-convolutional-neural-networks-496815db12a8

4.CIFAR-10 Image Classification in TensorFlow: https://towardsdatascience.com/cifar-10-image-classification-in-tensorflow- 5b501f7dc77c
