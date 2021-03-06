# Digits-Recognition

## About
The aim of this project is to implement different conventional classifiers to achieve hand-written
digits recognition, as well as performing transfer learning in an image classification task.

Following Algorithms were implemented:
1) Support Vector Machines (dimensionality reduction with PCA and MDA)
2) Multiclass Logistic Regression (dimensionality reduction with PCA and MDA)
3) Convolutional Neural Network

Transfer Learning has been implemented on the monkey species dataset.

## Results:
1. Support Vector machines:
    1. Linear Kernel - 93.68% (combined with PCA)
    2. Polynomial Kernel - 97.19% (combined with PCA)
    3. Radial Basis Kernel - 96.55% (combined with PCA)
2. Multiclass Logistic Regression - 92.56% (combined with PCA)
3. Convolutional Neural Network - 98.84%
4. Transfer Learning - The accuracy of a new model was increased from 51.66% to 95.22% when replaced 
with MobileNet model with pretrained weights on imagenet dataset.

## Datasets used:
1) [MNIST - Digit Recognition](http://yann.lecun.com/exdb/mnist/)
2) [Monkey Species - Transfer Learning](https://www.kaggle.com/slothkong/10-monkey-species/home)

## Required Libraries
1) Tensorflow
2) Scikit-Learn
3) Seaborn
4) Numpy
5) Matplotlib