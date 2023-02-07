# Brain MRI Image Generation using GANs
This project aims to generate realistic brain MRI images using Generative Adversarial Networks (GANs). In this project, three different GAN models are developed and trained (4-layered, 7-layered, and 15-layered). The results of the models are compared used different metrics. The thesis and the code used are available in this repository.

## Overview
This respository includes:
* Code for transforimng NIFTI files to JPG images.
* Thesis report explaining the methodology and results of the project.

## Requirements
To run the code, the following libraries are required:

* Python 3.x
* TensorFlow 2.x
* NumPy
* Matplotlib

## Usage
The code used for the samples extraction, training of the models and evaluating results can be found in the Jupyter notebook GAN_BRAIN_MRI.ipynb.

## Results
The results of the experiments are described in detail in the thesis report. In summary, increasing the number of samples in the training dataset and the number of training epochs improved the quality of the generated images. The 7-layered model provided the best results, with a good balance between computational resources and quality of generated images.

## Thesis
The thesis report is available in the root folder in PDF format. The report provides a detailed explanation of the methodology and results of the project.

## Conclusion
This project demonstrates the potential of GANs for generating realistic brain MRI images. The thesis compares how the amount of layers, epochs and sapmles affect the performance of the model. With further improvements, GANs have the potential to be used in medical imaging applications such as data augmentation, image synthesis, and even diagnosis assistance.
