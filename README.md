# 🌟 SFENet: Unleashing Spatial-Frequency Ensemble Networks for Robust Crop Health Monitoring 🌿🔬

[![Project Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/yourusername/crop-health-monitoring)
[![Python Version](https://img.shields.io/badge/Python-%E2%89%A73.7-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Paper](https://img.shields.io/badge/Paper-Coming%20Soon-lightgrey.svg)](https://arxiv.org/)

Welcome to the official repository of **SFENet**, our novel deep learning framework engineered for high-precision crop health monitoring. We tackle the critical challenge of identifying nutrient deficiencies in plant leaves with a cutting-edge approach that synergistically fuses spatial and frequency domain analysis through an ensemble of meticulously enhanced deep neural networks.

## ✨ Overview: Bridging Spatial and Spectral Insights for Agricultural Intelligence

Our work introduces **SFENet**, a powerful architecture that goes beyond traditional RGB-based analysis by deeply integrating **spatial-frequency domain features**. At its core, SFENet leverages an ensemble of three state-of-the-art convolutional neural networks—**DenseNet121**, **ResNeXt50**, and **Inception V3**—each augmented with our custom-designed **Spectral Guided Convolution (SGC)** and **Hierarchical Frequency Selector (HFS)** modules. This innovative combination allows the network to capture both intricate spatial details and crucial spectral characteristics inherent in leaf imagery, leading to superior nutrient deficiency detection in banana and coffee crops.

---

## 💡 Key Contributions: Pushing the Boundaries of Plant Phenotyping

- **Spatial-Frequency Fusion**: A novel integration of spatial and frequency domain information for richer feature representation.
- **Spectral Guided Convolution (SGC)**: An innovative convolutional block designed to explicitly extract and leverage fine-grained spectral features.
- **Hierarchical Frequency Selector (HFS)**: A multi-scale frequency selection mechanism to capture both localized and global spectral patterns.
- **Robust Ensemble Strategy**: A dynamic ensemble learning approach utilizing **Cohen’s Kappa-based weighting** and **soft voting** for enhanced prediction accuracy and generalization.
- **State-of-the-Art Results**: Achieved compelling performance with **91.68%** accuracy on the banana leaf dataset and **91.87%** on the coffee leaf dataset, outperforming existing methods.
- **Generalizable Framework**: Designed for adaptability across diverse crop types and environmental conditions, showcasing the potential for broad application in precision agriculture.

---

## 🛠️ Installation: Get SFENet Up and Running

### Prerequisites

- Python $\ge$ 3.7
- PyTorch $\ge$ 1.10
- torchvision $\ge$ 0.11
- Other dependencies (install via `requirements.txt`)

### Clone the Repository

```bash
git clone [https://github.com/yourusername/crop-health-monitoring.git](https://github.com/yourusername/crop-health-monitoring.git)
cd crop-health-monitoring
