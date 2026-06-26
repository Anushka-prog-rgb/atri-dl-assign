# Atri Assignment

## Overview of the whole assignment
This repo contains my implementaion of a feedForward neural network built from scratch using NumPy. The network is trained on the Fashion-MNIST dataset and supports multiple optimization algorithms including SGD, Momentum, Nesterov, RMSprop, Adam, and Nadam.

## Structure of this assignment
atri-dl-assign/
README.md
train.py
evaluate.py
network.py
optimizers.py
notebooks/
      experiments.ipynb

## Setup
###1.Clone repo
git clone https://github.com/Anushka-prog-rgb/atri-dl-assign.git
cd atri-dl-assign

### Install dependencies
pip install numpy pandas matplotlib keras wandb

### Training the model
python train.py  --epochs 10 --lr 0.001 --optimizer adam --hidden_layers 3 --hidden_size 128

### Evaluate the model
python evaluate.py --model_path saved_model.npy

## Progress
Question 1: Download Fashion-MNIST and visualize one sample per class
Question 2: Build flexible feedForward network (variable layers and neurons)
Question 3: Backpropagation with SGD, Momentum, Nesterov, RMSprop, Adam, Nadam
Question 4: Hyperparameter search using wandb sweeps
Question 5: Best validation accuracy summary
Question 6: Analysis using parallel coordinates plot and correlation summary
Question 7: Confusion matrix for best model on test set
Question 8: Cross-entropy loss vs squared error loss comparison
Question 10: Apply learning to MNIST dataset

## Dependencies
python 3.8+
NumPy
Pandas
Matplotlib
Keras (only for  loading the dataset)
wandb

## Notes
No automatic differentiation libraries are used
All matrix operations are implemented manually in Numpy
Test data is strictly kept separated from training throughout.  

report link
https://wandb.ai/zda23m016-iit-madras-zanzibar/atri-fashion-mnist/reports/Learning-to-Dress-How-Gradient-Descent-Teaches-Machines-to-Recognize-Fashion--VmlldzoxNzM1MjQzNg
