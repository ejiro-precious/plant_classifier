# Plant Seedling Classifier
My Capstone Project for Udacity's Machine Learning nanodegree will attempt to classify twelve different species of plants by image analysis. This project will utilize the dataset from Kaggle's Plant Seedlings Identification competition.

# Problem Statement

The problem being investigated here is a classification of seedling from an image using Convolutional neural Network (CNN). This can help improve better crop yield and better stewardship of the environment.

# Requirements
Python 3,
Keras(tensorflow)
pandas,
numpy, 
sklearn, 
seaborn, 
keras, 
PIL,
CV2

# WorkFlow
1) Explore the data: This involves importing the dataset, view samples of training data, number of images in the train dataset, species and image count.
2) Data Preprocessing: Here is will try to resize, normalise my images
3) Model Building: I will try to build a basic CNN and then, I will use transfer learning on top of VGG16 or Inception V3 network. This is because using a pre-trained network is efficient in CNN.
4) Algorithm Building: Once I have my model I will try to create an image classification algorithm that load and predict class using my model.

# Result
F1 Score based on transfer learning on Inception V3 of 0.92421 
As of now on the kaagle leader board there is an avearge F1 score of 1.0000