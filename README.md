# Basic CNN on CIFAR-10

This project implements a basic Convolutional Neural Network trained on the CIFAR-10 dataset using PyTorch.

## Features
- CNN from scratch
- Training and evaluation scripts
- W&B integration for logging

## How to Run
- Upload the config.yaml file in basic_cnn_cifar10 folder to the root directory
- Download the basic_cnn.ipynb file and simply run all the blocks

# ResNet18 Fine-Tuning on CIFAR-10

This project fine-tunes the ResNet18 model (from `torchvision.models`) on the CIFAR-10 dataset using PyTorch.

## Features

- Load pretrained ResNet18
- Replace final fully connected layer for 10 classes
- Option to freeze/unfreeze layers
- W&B integration for logging

## How to Run
- Upload the config.yaml file in the resnet18_cifar10 to the root directory
- Download the resnet18.ipynb file and simply run all the blocks