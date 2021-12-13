# WAE-Ensemble
Weighted Average Ensemble method for the semantic segmentation of biological electron microscopy images.

# Pre-trained models
ResNet34, InceptionV3, VGG19, SeResNet34, EfficientNet-B4

### Requirements

Software requirements are provided in the files.
GPU is crucial for training. 

### Dataset

Sample images for training and testing are available at https://lmb.informatik.uni-freiburg.de/resources/datasets/tem.en.html
For additional image request and questions regarding the codes, please contact: kavitha.shaga-devan@uni-ulm.de 

## Usage

1) The codes are given in the form of Google Colab notebook.
2) Train and test model according to the instruction given by the WAE_Ensemble notebook.
3) Use the Grad_CAM_EM notebook to perform the grad-cam verification. 


The Grad-CAM code in this repository has been adapted from https://github.com/kiraving/SegGradCAM.


