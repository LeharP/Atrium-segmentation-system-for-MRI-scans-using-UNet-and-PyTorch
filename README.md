# Atrium Segmentation System for MRI Scans using UNet and PyTorch

## Overview

This project implements a deep learning-based atrium segmentation system for MRI scans using the U-Net architecture, a well-known model for biomedical image segmentation. The system processes MRI data, applies data augmentation techniques, and trains a U-Net model using PyTorch and PyTorch Lightning to achieve high accuracy in segmenting atrial regions. The model achieves a Dice Loss-based accuracy of 95%, making it a reliable tool for medical image analysis.

## Features

- **MRI Data Preprocessing**: Converts MRI scans from NIfTI format to NumPy arrays and applies normalization techniques (Z-score normalization, Min-Max scaling) and cropping for uniformity across datasets.
- **Data Augmentation**: Enhances generalization by applying scaling, rotation, and elastic transformations, reducing the risk of overfitting.
- **U-Net Architecture**: Implemented using PyTorch, the U-Net model is designed for biomedical segmentation tasks.
- **PyTorch Lightning Integration**: The system leverages PyTorch Lightning for streamlined training, enabling modular, scalable, and efficient experimentation

