# Brain Tumor Segmentation Using 3D U-Net

## Overview
This project implements a 3D U-Net model for brain tumor segmentation using the BraTS 2020 (Brain Tumor Segmentation Challenge) dataset obtained from Kaggle. The goal is to accurately segment tumor regions from MRI scans, which is crucial for diagnosis and treatment planning.

## Dataset
The BraTS 2020 dataset consists of multimodal MRI scans (T1, T2, T1c, and FLAIR) with corresponding ground truth segmentations for different tumor types. The dataset can be downloaded from Kaggle [here](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation).

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Matplotlib
- Scikit-image

## Requirements
To run this project, you'll need the following packages:
- numpy
- tensorflow
- matplotlib
- scikit-image

You can install the necessary libraries using pip:

```bash
pip install numpy tensorflow matplotlib scikit-image
