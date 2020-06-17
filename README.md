# CNN_EMNIST_Letters
# By: Jeremy Rico
# Language: Python with Keras for TensorFlow

This project utilizes Google's TensorFlow and Keras to create a Convolutional Neural Network with two hidden layers. The network is trained on the EMNIST_Letters dataset with the goal of being able to classify handwritten characters. 

Dataset: EMNIST_Letters contains a large amount of handwritten images of each letter in the english alaphabet. Each image is 28x28px and they are all labeled to identfy which letter the image represents. 

The data is divided into training and testing data. However, for our purposes, we divided the training data into training and validation sets.

Workflow: The network is trained on the 100,000+ training samples and is programmed to stop when validation error rises to avoid overfitting. The network is then tested on the test set. 

For deatiled results, see the main program.
