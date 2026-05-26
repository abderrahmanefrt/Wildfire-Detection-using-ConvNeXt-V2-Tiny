# 🔥 Wildfire Detection using ConvNeXt V2 Tiny

A deep learning project for wildfire image classification using the powerful **ConvNeXt V2 Tiny** architecture.  
The model classifies images into two categories:

- `fire`
- `nofire`

This project uses **transfer learning**, **fine-tuning**, and modern computer vision techniques to achieve strong performance on wildfire detection tasks.



## 📌 Project Overview

Wildfire detection is an important computer vision application for environmental monitoring and disaster prevention.

In this project, we use a pretrained **ConvNeXt V2 Tiny** convolutional neural network and adapt it for binary image classification.

The notebook includes:

- Data preprocessing
- Data augmentation
- Model construction
- Training and fine-tuning
- Evaluation metrics
- Prediction on test images



## 🧠 Model Used

- **Architecture:** ConvNeXt V2 Tiny
- **Framework:** PyTorch
- **Technique:** Transfer Learning + Fine-Tuning



## 📂 Dataset Structure

```bash
dataset/
│
├── train/
│   ├── fire/
│   └── nofire/
│
├── validation/
│   ├── fire/
│   └── nofire/
│
└── testing/
