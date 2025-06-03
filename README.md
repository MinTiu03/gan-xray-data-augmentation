# GAN Chest X-ray Data Augmentation

This repository contains code for generating synthetic chest X-ray images using DCGAN, evaluating image quality using FID, and training a CNN classifier.

## Structure

- `notebooks/`: Jupyter notebooks for training GAN, computing FID, and classifying X-rays.
- `models/`: Placeholder for saved `.h5` models.
- `data/`: Placeholder for sample images if needed.

## Notebooks

1. **1_train_dcgan.ipynb** – Train DCGAN to generate NORMAL chest X-ray images.
2. **2_fid_evaluation.ipynb** – Calculate FID between real and generated images.
3. **3_cnn_classifier.ipynb** – Train CNN to classify chest X-ray into NORMAL or PNEUMONIA.
