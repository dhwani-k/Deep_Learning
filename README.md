# FNN for MNIST classification using PyTorch

This repository contains an implementation of a feedforward neural network (FNN) for MNIST classification using PyTorch in a Jupyter Notebook. The FNN architecture consists of three fully connected layers with ReLU activation functions. The model is trained using the cross-entropy loss function and the Adam optimizer.

Getting started
To run the code, you will need Python 3 and the following Python packages:

PyTorch
torchvision
matplotlib
Jupyter Notebook
To install these packages using pip, run the following command:

pip install torch torchvision matplotlib jupyter

Once you have installed the required packages, you can run the Jupyter Notebook using the following command:

jupyter notebook FNN_MNIST.ipynb

This will open the Jupyter Notebook in your default web browser. You can then run the code cells in the notebook to train the FNN model on the MNIST dataset and plot the training and testing loss curves.

Code structure
The code consists of a single Jupyter Notebook file, FNN_MNIST.ipynb, which contains the following components:

- FNN architecture definition
- MNIST dataset loading and data loaders creation
- Model training and testing loop
- Training and testing loss curve plotting
