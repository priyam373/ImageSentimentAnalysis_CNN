# ImageSentimentAnalysis_CNN
# Requirement:
This project predicts if a person is happy or sad. This is a binary classification model which can be used in sentiment analysis or emotion recognization to ascertain if a person is happy or sad.
# Data Gathering:
The data has been downloaded and gathered from the internet to train the deep neural network.
# EDA and Data Preprocessing:
The images which don't hold an appropriate extension (such as jpeg, jpg or png) or corrupt have been removed from the dataset.
data pipeline has been used to read the images from the source flolder and preprocess it including resizing all the images and creating a batch of 32 images to train the model. this has been done with the help of keras utlity called image_dataset_from_directory.
# Model building:
the pixles in the images have been scaled down to values between 0 and 1 and data has been split into train, validation and test data set.
  # Convolutional Operation: 
  to build a CNN, filtering and pooling layer has been used. filtering is to extract features out of the images such as edges or shapes and pooling layer is to reduce     the spatiald dimension and get the most important information out of the images:
  # Flattening: 
  the output of the CNN has been flattened so it can be passed through an ANN model. The Activation function is 'ReLU' for the hidden layer and 'Sigmoid' for the output layer to get the output in terms of 0 and 1.

# Model Evaluation:
model has been evaluated with the help of precision and recall matrix and accuracy parameter

# Saving the model:
the model has been saved into H5 file so that it can be used by anyone in any other application or can be deployed to an API.

