# 🧠 Brain MRI Image Segmentation with U-Net for Lower Grade Glioma Detection

This repository contains a deep learning pipeline for segmenting brain MRI images using a U-Net architecture to detect the presence of **lower grade gliomas** — a category of brain tumors that are critical to identify early for effective treatment planning.

---

## 📌 Project Overview

This project demonstrates the application of **U-Net**, a convolutional neural network architecture specifically designed for **biomedical image segmentation**, to classify and segment **brain MRI scans** based on the presence or absence of lower grade gliomas.

---

## 🎯 Objective

- Segment brain MRI images to highlight areas affected by lower grade gliomas.  
- Classify the presence or absence of gliomas from MRI data.  
- Support early diagnosis and aid radiologists in identifying tumors more accurately and efficiently.

---

## 🚀 Key Features

### 🔬 Model Architecture
- Uses **U-Net**, a powerful segmentation model tailored for medical imaging.
- Architecture optimized for precise pixel-level classification.

### 🧾 Dataset
- Labeled MRI brain scans annotated with the presence/absence of lower grade gliomas.
- Suitable for binary classification and segmentation tasks.

### 🧹 Preprocessing Pipeline
- Image resizing  
- Normalization  
- Format conversion (e.g., to NumPy arrays or tensors)

### 🏋️ Model Training
- Optimized hyperparameters (e.g., learning rate, loss function)
- Epoch checkpoints and validation tracking
- Real-time metrics and loss monitoring

### 📈 Performance & Results
- Achieves **notable segmentation accuracy**
- Effective tumor localization and classification
- Demonstrates deep learning’s power in medical diagnostics

---

## 📊 Applications

- Clinical decision support in neuro-oncology  
- Early-stage brain tumor diagnosis  
- Automation of MRI analysis workflows  

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy, OpenCV, Matplotlib  
- Jupyter Notebook  
- U-Net architecture  

---

## 📂 Repository Structure




Brain MRI Image Segmentation with U-Net for Lower Grade Glioma Detection
This notebook demonstrates the implementation of a U-Net model for brain MRI image segmentation to classify the presence of lower grade gliomas. The primary objective is to distinguish MRI scans based on whether they show evidence of lower grade gliomas, a type of brain tumor.

Key Features:
Model: U-Net architecture, widely used for biomedical image segmentation, tailored for precise detection and classification of brain structures.
Data: Brain MRI images labeled to indicate the presence or absence of lower grade gliomas.
Objective: Segment brain MRI images and accurately classify the presence of lower grade gliomas, aiding in early detection and diagnosis.
Highlights:
Preprocessing steps, including resizing and normalization, to enhance model performance.
Model Training using the U-Net architecture with optimized hyperparameters to achieve effective segmentation results.
Results: Achieves notable accuracy in identifying lower grade gliomas, demonstrating the potential for aiding diagnostic processes in medical imaging.
This project exemplifies the application of deep learning in medical imaging, with potential uses in improving diagnostic workflows in healthcare

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
