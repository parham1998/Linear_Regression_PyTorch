# Linear_Regression_PyTorch
Implementation of a simple Linear Regression model with Numpy & PyTorch library

In this project, I tried to test a Linear Regression model on simple one-dimensional data. the true line formula is (y = 2x + 7) + some random noise, and the model have to recognize weight: 2 and bias: 7 after 1000 epochs.
I made 100 data randomly and separate them into train and test sets. 80 data for a train set and 20 data for the test set.

### train and test data
![data](https://user-images.githubusercontent.com/85555218/127880177-0c6d41c5-f826-4507-8139-f171f1797c79.png)

This project consists of 2 files: main_numpy.py and main_pytorch.py.
In main_numpy.py I built the model from scratch, which means computing loss function, computing the gradient of the loss, and update parameters without any prepared classes.
and in main_pytorch.py I changed the type of data to tensor and used PyTorch classes to build the model.
the main goal of this project is to show and investigate the functionalities of PyTorch classes for training a model.

### predicted line with the aforementioned model
![model](https://user-images.githubusercontent.com/85555218/127882817-a8ab836c-7682-4de0-8e0b-91343aac3a9a.png)

### losses obtained in different epochs
![loss](https://user-images.githubusercontent.com/85555218/127883178-222eea71-6e95-46df-9eb0-4b1daa2a3db6.png)
