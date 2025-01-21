# Brain Tumor Segmentation  
**Brain Tumor Segmentation with W-Net and Deep Neural Networks**  

## Overview  
This project focuses on the segmentation of brain tumor regions in MRI images using advanced deep learning architectures such as W-Net and U-Net. The models were designed and fine-tuned to achieve high segmentation accuracy, with particular emphasis on delineating tumor boundaries for improved diagnostic precision. The project leverages datasets like BRATS 2020 and 2021 to ensure robustness across diverse tumor types and imaging conditions.  

## Key Features  
- **Architectures**: Designed and implemented W-Net and U-Net architectures optimized for medical image segmentation.  
- **Accuracy**: Achieved over 90% segmentation accuracy, with a **Mean Intersection Over Union (Mean IoU)** of 80% and a **Dice Score** demonstrating reliable tumor boundary detection.  
- **Model Evaluation**: Experimented with advanced deep learning blocks, including VGG16, ResNet, and DenseNet, to evaluate and refine performance.  
- **Optimization**: Enhanced computational efficiency and robustness through parameter tuning and model evaluation techniques.  
- **Datasets**: Utilized the BRATS 2020 and 2021 datasets, which include multimodal MRI scans with ground truth annotations for tumor regions.  

## Dataset  
The BRATS datasets used in this project include:  
- **MRI Modalities**: T1, T2, T1c (contrast-enhanced), and FLAIR.  
- **Annotations**: Pixel-level ground truth for tumor regions, including core, enhancing, and whole tumor regions.  

### Dataset Structure  
Organize the dataset as follows:  
```plaintext
dataset/
  ├── train/
  │   ├── MRI Scans/
  │   ├── masks/
  ├── validation/
      ├── MRI Scans/
      ├── masks/
  ```

## Results  
- **Accuracy**: Over 90%.  
- **Mean Intersection Over Union (Mean IoU)**: 78%.  
- **Dice Score**: 74%.  

### Example Results  


## Performance Evaluation  
### **Comparison Models**  
- VGG16, ResNet, and DenseNet blocks were evaluated for their performance in refining segmentation accuracy.  

### **Optimization Techniques**  
- Hyperparameter tuning for learning rates, batch sizes, and optimizer selection.  
- Data augmentation to enhance model generalization.  

---

## Project Highlights  
- **Boundary Detection**: Enhanced tumor boundary delineation for better diagnostic precision.  
- **Robustness**: Ensured consistent results across diverse datasets through rigorous evaluation and tuning.  
- **Scalability**: Models can be adapted for other medical imaging tasks beyond brain tumor segmentation.  
