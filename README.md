# 🧠 Brain Tumor Segmentation using Deep Learning

A high-precision deep learning pipeline for segmenting brain tumor regions in MRI scans using U-Net and W-Net architectures. Trained and evaluated on the BRATS 2020 and 2021 datasets, this project targets improved diagnostic clarity through robust medical image segmentation.

---

## 📌 Project Overview

This project explores deep convolutional neural networks for accurate brain tumor segmentation in multimodal MRI data. It focuses on segmenting tumor sub-regions (edema, enhancing core, and non-enhancing core) to assist radiologists in precise treatment planning.

Key techniques include:
- Custom **U-Net** and **W-Net** architectures
- Transfer learning with **VGG16**, **ResNet**, and **DenseNet** backbones
- Parameter tuning and augmentation strategies for generalization
- Evaluation using **Dice Score**, **IoU**, and **accuracy**

---

## 🧠 Architectures & Features

- 🔬 **Model Architectures:**  
  Designed U-Net and W-Net networks tailored for medical image segmentation.

- 📊 **Performance Metrics:**  
  - Accuracy: **95%**  
  - Mean IoU: **70%**  
  - Dice Score: **76%**

- 🚀 **Optimization:**  
  - Hyperparameter tuning  
  - Batch normalization  
  - Augmentation techniques for rotation, scaling, and flipping

- 🧪 **Backbone Evaluation:**  
  Integrated and compared **VGG16**, **ResNet**, and **DenseNet** as encoder blocks to refine spatial feature extraction and boost segmentation accuracy.

---

## 📁 Dataset

**BraTS 2020 & 2021** datasets were used, containing multi-modal 3D brain MRI scans.

- **Modalities:** T1, T2, T1c (contrast-enhanced), FLAIR
- **Annotations:** Ground truth masks including:
  - Whole tumor
  - Tumor core
  - Enhancing tumor

📸 **Sample MRI with Mask Overlay:**  
![Sample Image](https://github.com/Chetansai11/BRAIN_TUMOR_SEGMENTATION/blob/main/images/Untitled%20design.png)

---

## 📊 Results

| Metric      | Score |
|-------------|-------|
| Accuracy    | 95%   |
| Mean IoU    | 70%   |
| Dice Score  | 76%   |

📈 **Predictions Overview**  
- Whole tumor segmentation  
- Sub-region prediction for class differentiation

**Prediction Outputs:**  
![Prediction for all classes](https://github.com/Chetansai11/BRAIN_TUMOR_SEGMENTATION/blob/main/images/pre1.png)  
![W-Net Results](https://github.com/Chetansai11/BRAIN_TUMOR_SEGMENTATION/blob/main/images/wnetresult.png)

---

## 📦 Dataset Directory Structure

```plaintext
dataset/
  ├── train/
  │   ├── MRI Scans/
  │   ├── masks/
  ├── validation/
      ├── MRI Scans/
      ├── masks/

```


## 🔁 Model Pipeline

### 📘 Model Flow Diagram  
Visual overview of the segmentation workflow:

![Flowchart](https://github.com/Chetansai11/BRAIN_TUMOR_SEGMENTATION/blob/main/images/Flowcharts.png)

---

## ⚙️ Tools & Technologies

**Languages:**  
Python

**Frameworks:**  
PyTorch, OpenCV, NumPy, Matplotlib

**Techniques:**  
U-Net, W-Net, Transfer Learning, Medical Image Processing

---

## 🏆 Highlights

- 🎯 **Boundary Precision:** Superior tumor edge detection through hierarchical encoder-decoder architectures.
- 🔄 **Cross-Dataset Generalization:** Validated model performance across BRATS 2020 & 2021 datasets.
- 🩺 **Medical Adaptability:** Pipeline can be extended to other medical imaging tasks (e.g., lung segmentation, CT scans).

---

## 📬 Contact

**Chetan Sai Borra**  
📧 sai311235@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/chetan-sai-16a252251/)
