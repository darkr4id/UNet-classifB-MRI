# 🧠 Brain MRI Image Segmentation using U-Net & FPN for Lower Grade Glioma Detection

This repository implements a deep learning pipeline for segmenting brain MRI images using U-Net and FPN architectures to detect **lower grade gliomas** — slow-growing brain tumors that require early diagnosis for effective treatment.

---

## 📌 Project Overview

This project applies state-of-the-art segmentation models (U-Net and Feature Pyramid Networks) to classify and localize lower grade gliomas in T1-weighted brain MRI scans. It demonstrates a practical use of medical AI for assisting in neuro-oncological diagnostics.

---

## 🎯 Objective

- Segment brain MRIs to locate tumor regions
- Classify whether an MRI slice contains lower grade gliomas
- Provide interpretable predictions that support early tumor diagnosis

---

## 📂 Dataset

The dataset is loaded from a directory structure and includes:

- T1-weighted brain MRI scans
- Corresponding ground truth segmentation masks

Each sample contains:
- `images/` — raw brain MRI slices in `.tif` format  
- `masks/` — binary tumor masks
- https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation

*Note: The dataset appears to be pre-annotated. If using the BraTS dataset or any clinical source, proper licensing and citation are required.*

---

## 🧹 Preprocessing Steps

The notebook performs several preprocessing operations:

- Image resizing to 256×256 pixels
- Normalization of pixel intensity values to [0,1]
- Conversion to grayscale (if applicable)
- Conversion of masks into binary arrays
- Augmentation-ready data loading using custom generators

---

## 🏗️ Model Architectures

### ✅ U-Net:
- Standard encoder–decoder structure with skip connections
- Designed for biomedical segmentation

### ✅ FPN (Feature Pyramid Network):
- Multi-scale feature learning
- Enhances fine-grained segmentation at different spatial resolutions

---

## 🏋️ Training Details

- Optimizer: Adam  
- Loss function: Binary Cross-Entropy (BCE)  
- Evaluation metric: Dice Coefficient  
- Epochs: 25 (can be modified)  
- Batch size: 16  

Trained using Keras with TensorFlow backend.

---

## 📈 Results

The model outputs:
- Segmentation masks that closely align with ground truth
- Dice coefficients during training showing learning progress
- Sample visualizations comparing predictions vs. true masks

Performance appears qualitatively good, though exact accuracy metrics (e.g., Dice score values) aren't logged numerically in the notebook.

---

## 🖼️ Sample Output


![dataset](https://github.com/user-attachments/assets/bc37a7d6-9a72-4797-b890-533f681b33ca)


![image](https://github.com/user-attachments/assets/ef4ca5e2-aa39-47ef-9b3d-ba6f01647057)

![image](https://github.com/user-attachments/assets/a6fff1d1-1e9c-4603-92f9-a849f3f104c5)
![image](https://github.com/user-attachments/assets/b48420ee-67ea-426f-9ea1-bec5987d4991)
![image](https://github.com/user-attachments/assets/da5a4ca8-bd93-4047-a200-8beaa8baa5c5)
![image](https://github.com/user-attachments/assets/34685633-747e-4296-b783-b49ee4ebc27f)

![til](https://github.com/user-attachments/assets/549eaa8b-3c68-40fa-a994-9dc6f3fb9159)

Future work
-More epochs
-Different UNet backbones.

Reference
Kaggle, tutorial on UNet based image segmentation for biomedical applcations
https://www.kaggle.com/competitions/hubmap-kidney-segmentation/discussion/200955
https://www.kaggle.com/code/akshitsharma1/unet-architecture-explained-in-one-shot-tutorial

This page and project is still under construction, 2025 May.
