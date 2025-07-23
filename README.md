
#Breast Ultrasound Multi-task Learning with PyTorch 🩺🧠

This project implements a **multi-task deep learning model** for **breast ultrasound image analysis**, combining:

- **Lesion segmentation** (using U-Net)
- **Lesion classification** (benign / malignant / normal)

### 🔧 Features
- Built with **PyTorch**
- Custom preprocessing pipeline with Gaussian filtering, normalization, and resizing
- **Multi-task architecture**: shared encoder, task-specific heads
- Visualization tools:
  - Input image
  - Segmentation heatmap (sigmoid output)
  - Binarized mask overlay on image
  - Classification probabilities bar chart
  - Preprocessed vs raw image comparison

### 📊 Dataset
- [BUSI Dataset](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)
- Contains labeled ultrasound images: benign, malignant, and normal

### 📌 Status
Model trained, evaluated, and visualized successfully. Supports testing on:
- Random validation samples
- Custom user-provided images

### 🧠 Applications
- Computer-aided diagnosis
- Medical image analysis research
- Multi-task learning in healthcare
- Also i tried Attention u net for better IOU ratio.
  
