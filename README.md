<p align="center">
  <a href="https://github.com/XpressAI/xircuits/tree/master/xai_components#xircuits-component-library-list">Component Libraries</a> •
  <a href="https://github.com/XpressAI/xircuits/tree/master/project-templates#xircuits-project-templates-list">Project Templates</a>
  <br>
  <a href="https://xircuits.io/">Docs</a> •
  <a href="https://xircuits.io/docs/Installation">Install</a> •
  <a href="https://xircuits.io/docs/category/tutorials">Tutorials</a> •
  <a href="https://xircuits.io/docs/category/developer-guide">Developer Guides</a> •
  <a href="https://github.com/XpressAI/xircuits/blob/master/CONTRIBUTING.md">Contribute</a> •
  <a href="https://www.xpress.ai/blog/">Blog</a> •
  <a href="https://discord.com/invite/vgEg2ZtxCw">Discord</a>
</p>






<p align="center"><i>Xircuits Component Library for integrating PyTorch! Build and deploy machine learning models with ease.</i></p>

## Xircuits Component Library for PyTorch  

This library integrates PyTorch into Xircuits workflows, providing tools for seamless model development, training, and general PyTorch operations. It streamlines complex machine learning tasks with modular components.

## Table of Contents

- [Preview](#preview)
  
- [Prerequisites](#prerequisites)
- [Main Xircuits Components](#main-xircuits-components)
- [Try the Examples](#try-the-examples)
- [Installation](#installation)



## Preview 

### PytorchTrainModel Example

![PytorchTrainModel](https://github.com/user-attachments/assets/d494a80a-2e50-46c7-b663-16a0495ecef0)

### PytorchTrainModel Result

<img src="https://github.com/user-attachments/assets/1719cd3f-1b03-495d-a5a0-690ca74f6662" alt="PytorchTrainModel result" />

### PytorchPredictFromModel Example

![PytorchPredictFromModel](https://github.com/user-attachments/assets/60be010e-9dde-4dea-9de4-063951bce6b4)


### PytorchPredictFromModel Result

<img src="https://github.com/user-attachments/assets/2673e1d5-d581-4c9d-8c52-9d19dca7d9e4" alt="PytorchPredictFromModel result"  />

### PytorchTrainCustomNN Example

![PytorchTrainCustomNN](https://github.com/user-attachments/assets/7da9f1f4-762e-44f8-bc49-76b8f8d0c145)

### PytorchTrainCustomNN Result

<img src="https://github.com/user-attachments/assets/e42d46da-26e4-46c6-ae71-1c4b74ce6ec2" alt="PytorchTrainCustomNN result"  />

## Prerequisites

Before you begin, you will need the following:

1. Python3.9+.
2. Xircuits.

## Main Xircuits Components 

### TorchModel Component:
Defines a custom PyTorch model with optional flattening and a configurable optimizer and loss function for training.

<img src="https://github.com/user-attachments/assets/f5122457-b6aa-45b4-b350-361c2bc23ade" alt="TorchModel" width="200" height="150" />

### TorchAddLinearLayer Component:
Adds a Linear Layer to a sequential model with specified input and output features.

<img src="https://github.com/user-attachments/assets/bc301ff9-7e1f-4e4d-bbf4-a65504ffd4e3" alt="TorchAddLinearLayer" width="200" height="125" />

### TorchAddConv1DLayer Component:
Adds a 1D convolutional layer with configurable kernel size, stride, padding, and other parameters.

<img src="https://github.com/user-attachments/assets/b362d044-5110-40a3-af68-e7f154cf01cc" alt="TorchAddConv1DLayer" width="200" height="225" />

### TorchAddTransformerEncoderLayer Component:
Inserts a Transformer Encoder layer with multi-head attention and configurable feedforward dimensions and activation.

### TorchAddTransformerDecoderLayer Component:
Adds a Transformer Decoder layer with attention mechanisms and flexible feedforward configurations.

### TorchLSTM Component:
Creates an LSTM layer for sequence modeling, supporting options for bidirectionality, dropout, and projection.

### TorchAddReluLayer Component:
Adds a ReLU activation layer to a model, applying non-linearity to enhance model learning.

### TorchAddDropoutLayer Component:
Incorporates a Dropout layer to reduce overfitting by randomly zeroing out input elements during training.

## Try the Examples
We have provided an example workflow to help you get started with the PyTorch component library. Give it a try and see how you can create custom PyTorch components for your applications.

### PytorchTrainModel
This workflow automates PyTorch model training by connecting modular components for data loading, training, testing, and saving. It simplifies complex training pipelines, reduces boilerplate code, and ensures reusability across projects.

### PytorchPredictFromModel
This workflow demonstrates a PyTorch-based prediction pipeline. It automates the process of loading a saved model, preprocessing an input image into a tensor, and predicting the image's class using predefined labels.

### PytorchTrainCustomNN
This workflow demonstrates training a custom neural network using PyTorch components, allowing flexible layer and parameter configurations.


## Installation
To use this component library, ensure that you have an existing [Xircuits setup](https://xircuits.io/docs/main/Installation). You can then install the PyTorch library using the [component library interface](https://xircuits.io/docs/component-library/installation#installation-using-the-xircuits-library-interface), or through the CLI using:
```
xircuits install pytorch
```
```
# base Xircuits directory
git clone https://github.com/XpressAI/xai-pytorch xai_components/xai_pytorch
pip install -r xai_components/xai_pytorch/requirements.txt 
```