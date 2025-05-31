# SFENet
# **📚 Crop Health Monitoring Using Deep Learning: Detecting Nutrient Deficiencies in Leaves 🍃**

Welcome to the official repository for our **Precision Agriculture** project, where we leverage cutting-edge deep learning techniques to monitor the health of economic crops! This project addresses a critical challenge in agriculture: detecting nutrient deficiencies in plant leaves through high-performance image classification models.

## **🔍 Overview**

This repository presents an innovative approach that integrates **spatial-frequency domain features** with **ensemble deep learning** to accurately detect nutrient deficiencies in crops. By using a combination of **DenseNet121**, **ResNeXt50**, and **Inception V3** models, each enhanced with custom **Spectral Guided Convolution (SGC)** and **Hierarchical Frequency Selector (HFS)** modules, our method achieves state-of-the-art performance in classifying banana and coffee leaf images.

---

## **💡 Key Features**

- **Ensemble Learning**: Combines the power of three advanced models—DenseNet121, ResNeXt50, and Inception V3—for robust classification.
- **Spectral Guided Convolution (SGC)**: Captures fine-grained frequency features embedded in leaf images.
- **Hierarchical Frequency Selector (HFS)**: Focuses on multi-frequency, multi-scale features to capture both local and global patterns in the images.
- **Dynamic Weight Allocation**: Adapts model predictions based on **Cohen’s Kappa coefficient** and **soft voting**, ensuring optimal performance and generalization.
- **State-of-the-art Performance**: Achieves **91.68%** and **91.87%** accuracy on the banana and coffee leaf datasets, respectively.
- **Robust Generalization**: Ensures the model works efficiently across different crop types and environmental conditions.

---

## **🚀 Installation & Setup**

### **Clone the Repository**

To get started, simply clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/crop-health-monitoring.git
cd crop-health-monitoring
