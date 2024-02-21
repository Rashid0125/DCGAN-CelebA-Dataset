# DCGAN Implementation with CelebA Dataset
## Overview
This repository contains an implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) applied to the CelebA dataset. The DCGAN is a type of generative model that uses convolutional neural networks to generate realistic images.

## Files
DCGAN.ipynb: This Jupyter Notebook file contains the implementation of the DCGAN using TensorFlow and Keras. It includes the model architecture, training process, and image generation.

training_progress.gif: This GIF file visually represents the evolution of the training progress over epochs. It provides a quick overview of how the generated images improve over time.


![training_evolution](https://github.com/Rashid0125/DCGAN-CelebA-Dataset/assets/102589680/b6b03921-2f23-4913-bf24-0c77923004fa)


## Prerequisites
Make sure you have the following dependencies installed:

-----
gdown               4.7.3
matplotlib          3.7.1
numpy               1.25.2
session_info        1.0.0
torch               2.1.0+cu121
torchvision         0.16.0+cu121

You can install these dependencies using the following command:

```bash
pip install gdown==4.7.3 matplotlib==3.7.1 numpy==1.25.2 torch==2.1.0+cu121 torchvision==0.16.0+cu121
```
-----

My Python Version :  3.10.12 

-----

## Usage
Open and run the DCGAN.ipynb notebook in a Jupyter environment.

Follow the instructions and comments in the notebook to understand the implementation and train the DCGAN model.

Monitor the training progress and refer to the generated images to assess the quality of the generated faces.

The training_progress.gif file provides a quick visual summary of how the generated images evolve during training.

## Dataset
This implementation uses the CelebA dataset, a large-scale face attributes dataset with more than 200,000 
celebrity images. You can download the CelebA dataset from the official website.

After downloading, extract the dataset and ensure that the file structure aligns with the paths specified in the notebook.

## Acknowledgments
The DCGAN architecture and training process are based on the original paper by Radford et al.: Unsupervised Representation 
Learning with Deep Convolutional Generative Adversarial Networks.

CelebA dataset: Large-scale CelebFaces Attributes (CelebA) Dataset.

Feel free to reach out for any questions or feedback!
