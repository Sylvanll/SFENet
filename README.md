# 🌟 SFENet: Unleashing Spatial-Frequency Ensemble Networks for Robust Crop Health Monitoring 🌿🔬

[![Project Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/yourusername/crop-health-monitoring)
[![Python Version](https://img.shields.io/badge/Python-%E2%89%A73.7-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Paper](https://img.shields.io/badge/Paper-Coming%20Soon-lightgrey.svg)](https://arxiv.org/)

Welcome to the official repository of **SFENet**, our novel deep learning framework engineered for high-precision crop health monitoring. Addressing the critical need for effective nutrient deficiency detection in economic crops, SFENet introduces an innovative approach that synergistically integrates **spatial-frequency domain features** through a powerful **ensemble of deep learning models**.

## ✨ Overview: Synergizing Spatial and Frequency-domain Intelligence for Precision Agriculture

In the advancement of precision agriculture, monitoring the health of economic crops is paramount. Detecting nutrient deficiencies in leaves poses significant challenges, particularly in discerning subtle visual cues and managing data variability. To address this, we propose **SFENet**, a novel method that meticulously integrates spatial-frequency domain features within an ensemble deep learning framework.

Our approach constructs a robust ensemble comprising **DenseNet121**, **ResNeXt50**, and **Inception V3** models. Each constituent model is enhanced with our custom-designed **Spectral Guided Convolution (SGC)** and **Hierarchical Frequency Selector (HFS)** modules, enabling robust extraction of both spatial and frequency-based characteristics from leaf imagery.

The **SGC module** is specifically engineered to capture rich frequency information inherent in leaf images, further enhanced by **frequency-domain contrast regularization** to improve the discrimination of subtle features. Complementarily, the **HFS module** dynamically focuses on **multi-frequency, multi-scale features**, significantly improving the network's attention to both localized and global patterns within the images.

To optimize the ensemble's predictive power, we employ a **dynamic weight allocation mechanism** based on the **Cohen’s Kappa coefficient** and **soft voting**. This adaptive strategy enhances the generalization capability and overall accuracy of our predictions.

## 💡 Key Contributions: Achieving State-of-the-Art Crop Health Assessment

- **Spatial-Frequency Fusion**: A novel integration of spatial and frequency domain information for richer and more discriminative feature learning.
- **Spectral Guided Convolution (SGC)**: A specialized convolutional module designed to effectively extract frequency information, bolstered by frequency-domain contrast regularization.
- **Hierarchical Frequency Selector (HFS)**: A dynamic mechanism that focuses on multi-frequency, multi-scale features, capturing both local and global spectral nuances.
- **Dynamic Ensemble Learning**: An adaptive ensemble strategy utilizing Cohen’s Kappa-based weighting and soft voting to enhance generalization and accuracy.
- **State-of-the-Art Performance**: Achieved **91.68%** accuracy on the banana leaf dataset and **91.87%** on the coffee leaf dataset, demonstrating superior performance compared to existing methods.
- **Robust Generalization**: The experimental results on diverse datasets confirm the method’s robustness and its potential for broad application in crop health monitoring, advancing the field of precision agriculture.

---

## 🛠️ Installation: Get SFENet Ready

### Prerequisites

- Python $\ge$ 3.7
- PyTorch $\ge$ 1.10
- torchvision $\ge$ 0.11
- Other dependencies (install via `requirements.txt`)

### Clone the Repository

```bash
git clone [https://github.com/yourusername/crop-health-monitoring.git](https://github.com/yourusername/crop-health-monitoring.git)
cd crop-health-monitoring
