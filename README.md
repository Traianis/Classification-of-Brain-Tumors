# Classification-of-Brain-Tumors

# Overview

This project focuses on classifying brain tumors from MRI images using deep learning techniques. The model is trained on a dataset of MRI scans labeled into four categories:

-Glioma Tumor

-Meningioma Tumor

-Pituitary Tumor

-No Tumor

The implementation uses PyTorch, MONAI, and ResNet50 for image classification. Several preprocessing techniques are applied, including image resizing, Gaussian blur, CLAHE, and Sobel edge detection.

# Dataset

The dataset consists of MRI scans categorized into four classes. The images are preprocessed before training:

-Conversion to grayscale

-Histogram equalization (CLAHE)

-Edge detection (Sobel)

-Gaussian blurring

-Resizing to (224, 224)

# Model Architecture

The model uses ResNet50, with the final fully connected layer modified to classify four tumor types. The model is trained using cross-entropy loss and optimized with SGD.

# Results

Raport1.pdf

Raport2.pdf
