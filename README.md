# Fruit-freshness-detection-using-CNN
Freshness and Ripeness Detection using CNN This project uses a Convolutional Neural Network (CNN) to classify images of fruits into six categories based on their freshness and ripeness: fresh apples, rotten apples, fresh bananas, rotten bananas, fresh oranges, and rotten oranges.

**Project Overview**
The goal of this project is to detect whether a given fruit is fresh or rotten using image classification techniques. The dataset contains images of different fruits in their fresh and rotten states, and the CNN model is trained to predict the freshness of the fruits with the following categories:

Fresh Apples| Rotten Apples|  Fresh Bananas|  Rotten Bananas|  Fresh Oranges|  Rotten Oranges|

**Installation of Prerequisites**
1)Python 3.x 
2)TensorFlow/Keras 
3)NumPy

**Dataset Preparation** 
The dataset should be organized into training and testing sets. Each of these sets should contain subfolders for the fruit categories:

freshapples/ rottenapples/ freshbanana/ rottenbanana/ freshoranges/ rottenoranges/ If you don't have a validation set, you can use the validation_split parameter when training the model to split your training data into training and validation subsets.

**Model Training**
The model is a Convolutional Neural Network (CNN) built using Keras. It consists of several convolutional, max pooling, and dropout layers to prevent overfitting.
To train the model, run the following: python main.py You can adjust hyperparameters such as batch size, learning rate, and the number of epochs.
My hyperparameters:
Batch Size: 16
Learning Rate: Optimizer: Adam: 0.001
Epochs: 50

**Results**
The model achieves an accuracy of 97.19% on the training set and 96.16%% on the validation/test set. Here are the detailed metrics:

Training Accuracy: 97.19% Validation Accuracy: 97.14% Test Accuracy: 96.16%


