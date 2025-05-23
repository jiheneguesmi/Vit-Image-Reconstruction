# Vit-Image-Reconstruction

This repository contains implementations and experiments for image reconstruction using Vision Transformers (ViT) and Autoencoders. The notebooks demonstrate various techniques, including pretrained ViT encoders and custom Autoencoder architectures.

---

## Table of Contents
- [Overview](#overview)
- [Notebooks](#notebooks)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

---

## Overview

Image reconstruction involves restoring images from encoded representations or corrupted versions. This project explores:

- **Vision Transformers (ViT)** with pretrained encoders for reconstruction tasks.
- **Custom Autoencoder architectures** in TensorFlow/Keras.

---

## Notebooks

The repository includes the following Jupyter Notebooks:

### `AutoEncoderReconstructingImages.ipynb`
- Implements an Autoencoder for image reconstruction.
- Uses the `oxford_flowers102` dataset for training and testing.
- Includes visualization of reconstructed images.

### `Vit with Pretrained Encoder V.2.ipynb`
- Explores a pretrained Vision Transformer encoder for reconstruction.
- Includes fine-tuning techniques for ViT.

### `Vit with Pretrained encoder V.1.ipynb`
- A preliminary implementation of Vision Transformers for image reconstruction.
- Focuses on dataset preprocessing and initial experimentation.

---

## Installation

To run the notebooks, ensure **Python 3.11** and the required libraries are installed.

Install dependencies 


## Results

### Autoencoder
- Successfully reconstructs images from the `oxford_flowers102` dataset.
- Example visualization:


| ![image](https://github.com/user-attachments/assets/e3db9050-4c25-4f7f-8fcf-34d74b8499e5) | 

 | ![image](https://github.com/user-attachments/assets/5b4f8d44-b94e-415e-ba30-33cf69e679e4)
 |



### Vision Transformers
- Pretrained ViT models show promising results in encoding and decoding images.
- Fine-tuning ViT improves reconstruction accuracy significantly.
