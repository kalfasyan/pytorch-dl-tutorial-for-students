# Pytorch DL Tutorial For Students

This repository contains a Jupyter notebook called TUTORIAL.ipynb that shows how to train a deep learning model in PyTorch to classify dog breeds. The notebook uses the ResNet-18 architecture and is trained on a subset of Stanford Dogs Dataset which contains 120 breeds of dogs.

## Requirements
Python 3.6 or higher
See requirements.txt for required libraries

## Preparations

### Creating a Conda Environment and Installing Libraries with Pip

These instructions will guide you through creating a new Conda environment called `dltut`, installing pip with Conda, and using pip to install libraries from a requirements file.

#### Prerequisites

- Conda is installed on your system. If not, you can download and install it from the [Anaconda website](https://www.anaconda.com/products/individual).

#### Steps

1. Open anaconda prompt on your computer (`Start button --> type Anaconda prompt`). You should now see `(base)` at the start of your prompt.
2. Create a new Conda environment called "dltut" by typing the following command: `conda create --name dltut`
3. Activate the new environment by typing: `conda activate dltut`
4. Install pip with Conda by typing: `conda install pip -y`  
5. Install some other jupyter notebook dependencies: `conda install nb_conda_kernels ipywidgets ipykernel -y`  
  
Now you are ready to go the the *Usage* section.  

## Usage
1. Clone the repository:
`git clone https://github.com/your_username/pytorch-dog-breed-classifier.git`  
(in case you don't have git installed, you can download it from [here](https://git-scm.com/download/win)).  
2. Install the required libraries by running the following command:
`pip install -r requirements.txt` (you have to run this command from within the repository folder).  
3. Extract `dogs.zip` into the project directory (if on Windows, otherwise the notebook will extract it for you).  
4. Start Jupyter Lab and open the **TUTORIAL.ipynb** file: `jupyter-lab` (from the project folder)  
5. Follow the instructions in the notebook to train and test the model.

## Files
**TUTORIAL.ipynb**: Jupyter notebook with the tutorial code  
**dogs.zip**: Compressed file containing the subset of the Stanford Dogs Dataset  
**requirements.txt**: List of required libraries  

## Credits
The ResNet-18 implementation is adapted from the official PyTorch documentation: https://pytorch.org/docs/stable/_modules/torchvision/models/resnet.html
The Stanford Dogs Dataset is provided by the Stanford Vision Lab: http://vision.stanford.edu/aditya86/ImageNetDogs/
