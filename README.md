# Phishing URL Detection Using Deep Learning
This project implements a feed forward neural network, a deep learning model with Multilayer Perceptron (MLP) for detecting  phishing URLs . The model is analyzed and trained with various URL's features, such as URL length and special characters, to detmine a  websites as phishing or legitimate. This project demonstrates the potential of deep learning in privacy and security for identifying phishing threats.
# Features
Deep Learning Architecture: The model is based on a fully connected feedforward neural network (MLP) with multiple layers, ReLU activation, and a sigmoid output for binary classification.

High Performance: Achieved high accuracy, precision, and recall during validation and testing phases.

# Dataset
This dataset consists of 247950 instances, of which 128541 are from phishing URLs and 119409 are from legitimate URLs.   It encompasses 41 features and 1 target variable (0=legitimate,1=phishing), making it suitable for implementing machine learning algorithms to identify phishing attacks. 

Due to its large size, the dataset could not be uploaded to this repository

Dataset Link : https://data.mendeley.com/datasets/6tm2d6sz7p/1

# Deep Learning Model

 Primarly a Feed Forward Neural Network (FNN )with Multilayer Perceptron (MLP) model is
 selected from github.

 Github LInk : https://github.com/shaheerAlam1/detecting-phishing-websites- using-deep-learning

 The original model was configured to allocate 75 percent
 of the data for training and 25 percent for validation. But the
 model had no testing phase.
 
 Several updates have been made to enhance the model.
 The data is splitted as 80 percent for training, 10 percent for
 validation, and 10 percent for testing.
 
 Additionally, I have used a different and a larger dataset
 compared to the original model for training, validation, and
 testing to evaluate the model’s performance.

 # Result
 
During testing the model achieved :

Test Accuracy: 91.93%
Test Precision: 93.51%
Test Recall: 89.45%
Test Loss: 0.196



