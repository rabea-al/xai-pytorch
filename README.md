

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

## Xircuits Comprehensive PyTorch Libraries

These libraries collectively provide extensive functionalities for integrating PyTorch into Xircuits workflows, encompassing both general PyTorch operations and neural network-specific tasks.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started with PyTorch XAI Components](#getting-started-with-pytorch-xai-components)
- [Try The Examples](#try-the-examples)
- [Components Overview](#components-overview)
- [Contributing](#contributing)

## Prerequisites

Before using this library, you’ll need the following:

1. **Python 3.8** or higher
2. **Xircuits**
3. The following Python packages:
   - **torch**
   - **torchvision**
   - **pillow**


## Installation

To use this component library, ensure that you have an existing [Xircuits setup](https://xircuits.io/docs/main/Installation). You can then install the PyTorch library using the [component library interface](https://xircuits.io/docs/component-library/installation#installation-using-the-xircuits-library-interface), or through the CLI using:


```bash
xircuits install pytorch
```

Alternatively, you may clone this repository into your `xai_components` directory and install it manually:

```bash
# To clone the PyTorch component library into your Xircuits project directory
git clone https://github.com/XpressAI/xai-pytorch.git xai_components/xai_pytorch
```
```bash
# Install required dependencies
pip install -r xai_components/xai_pytorch/requirements.txt
```

## Getting Started With PyTorch XAI Components

After successfully installing the necessary libraries and components, you are ready to explore the PyTorch XAI Components Library. This library enables you to develop comprehensive machine learning workflows within Xircuits. Refer to the provided documentation and examples to master the integration, customization, and utilization of deep learning components using PyTorch XAI.

## Try The Examples

We have provided an example workflow to help you get started with the PyTorch XAI Components Library. Give it a try and see how you can create a custom deep learning workflow for your projects.

### PytorchTrainModel

This example demonstrates the initial setup of a machine learning workflow in Xircuits using the PyTorch XAI Components Library. It involves training a custom neural network model on your dataset. This step is crucial as the output model will be used in subsequent examples.

### PytorchPredictFromModel

Following the training process, this example shows how to use the trained model to make predictions. It leverages the model trained by the `PytorchTrainModel` to demonstrate the prediction process on new data, showcasing how to integrate trained models into practical applications.

### PytorchTrainCustomNN

This example extends the capabilities of the PyTorch XAI Components by illustrating how to train a more complex, custom neural network. It utilizes advanced features of PyTorch to tailor a neural network to specific needs beyond standard models.

**Note:** It is important to run the `PytorchTrainModel` example first, as the other examples depend on the output from this initial training step.


## Components Overview

The PyTorch XAI Components Library offers an array of components tailored for various stages of the deep learning lifecycle. Explore these components and refer to their documentation to enhance your ability to develop sophisticated deep learning workflows.

## Contributing

We welcome contributions to the **Pytorch XAI Components Library**! If you would like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Open a pull request with a detailed description of your changes.

Please feel free to suggest new components, improvements, or optimizations. If you encounter any issues or have ideas for enhancements, you can open an issue in the repository.

---

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.