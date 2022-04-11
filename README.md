# WAE-Net
This repository contains codes for the paper "Weighted Average Ensemble-Based Semantic Segmentation in Biological Electron Microscopy Images".

# Pre-trained models used in this work
ResNet34, InceptionV3, VGG19, SeResNet34, EfficientNet-B4

### Requirements

Software requirements are provided in the files.
GPU is crucial for training. 

###  Pre-trained weights and Image dataset

Pre-trained weights for all dataset are available at https://drive.google.com/drive/folders/1gctQi1S-0ruOJR_nHF_J5BycCeM5AltQ?usp=sharing

All image datasets (1-7) are available for training and testing at https://drive.google.com/drive/folders/1Vkl0fgWk4Qf4csPtrfdnYqFro0cA85J3?usp=sharing


## Usage

1) The codes are given in the form of Google Colab notebook.
2) Train and test model according to the instruction given by the WAE_Net_Ensemble notebook.
3) Use the WAE-Net_Grad_CAM_Ensemble notebook to perform the Grad-CAM verification. 


The Grad-CAM code in this repository has been adapted from https://github.com/kiraving/SegGradCAM.

Dataset 4-7 are publicly available images from  https://lmb.informatik.uni-freiburg.de/resources/datasets/tem.en.html

