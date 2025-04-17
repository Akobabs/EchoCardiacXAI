# 🫀 CardiacMotionXAI

*A computer vision system to detect abnormal cardiac motion in echocardiogram videos using optical flow, convolutional neural networks (CNNs), and explainable AI (Grad-CAM).*

Developed for **CSE 6367: Computer Vision, Fall 2025** at the **University of Texas at Arlington**  
**Supervisor**: Professor Marnim Galib

---

## 📖 Overview

This repository hosts the planned implementation of a computer vision project focused on detecting abnormal cardiac motion in echocardiogram videos using the **EchoNet-Dynamic** dataset. The system integrates:

- **Optical Flow**: For motion feature extraction
- **CNNs**: For classification of normal vs. abnormal motion
- **Grad-CAM**: For explainable predictions, highlighting key frames/regions

🗓️ **Status**: Planning Phase (April 17, 2025)  
🧠 **Focus**: Robust classification and interpretability in medical diagnostics

---

## 🎯 Objectives

- **Primary Goal**: Classify echocardiogram videos as normal or abnormal based on cardiac motion patterns.
- **Explainability**: Use Grad-CAM to visualize frames or regions driving predictions, enhancing trust in medical applications.
- **Course Alignment**: Leverage CSE 6367 techniques, including optical flow, deep learning, and feature extraction.

---

## 📊 Dataset

**EchoNet-Dynamic**: A dataset of 10,030 echocardiogram videos from Stanford University’s Artificial Intelligence in Medicine and Imaging (AIMI) initiative, annotated with ejection fraction and ventricle tracings.

- **Project Subset**: 1,000 videos (500 normal, 500 abnormal) for balanced training and computational feasibility.
- **Sources**:
  - [EchoNet-Dynamic Dataset](https://stanfordaimi.azurewebsites.net/datasets/echonet-dynamic/)
  - [Papers With Code](https://paperswithcode.com/dataset/echonet-dynamic)

---

## 🛠️ Methodology

1. **Motion Feature Extraction**:
   - Apply optical flow to track cardiac motion (e.g., ventricle wall movement) across video frames.
2. **Classification**:
   - Fine-tune a pre-trained CNN (e.g., ResNet) to classify videos as normal or abnormal.
3. **Explainable AI**:
   - Implement Grad-CAM to generate heatmaps highlighting decision-critical frames or regions.
4. **Evaluation**:
   - Measure performance with accuracy, precision, recall, and F1-score.
   - Qualitatively validate Grad-CAM outputs against relevant cardiac motion.

---

## 🧰 Tools and Technologies

- **Language**: Python
- **Libraries**:
  - [OpenCV](https://opencv.org/) for optical flow
  - [PyTorch](https://pytorch.org/) for deep learning
  - [Captum](https://captum.ai/) for Grad-CAM
- **Environment**: Google Colab or local GPU setup
- **Data Processing**: `pydicom` for DICOM-format echocardiograms

---

## 📅 Project Timeline

| Phase | Duration | Activities |
|-------|----------|------------|
| 🧪 Planning | Apr–Aug 2025 | Dataset exploration, tool setup, literature review |
| 📝 Proposal | Week 6 | Submit official proposal |
| 🔧 Development | Weeks 7–12 | Preprocessing, training, Grad-CAM integration |
| 📊 Final Report | Week 14 | Submit report with results & analysis |

---

## 🚧 Current Status

As of **April 17, 2025**, this project is in the **planning phase**. This repository is a placeholder for the Fall 2025 implementation. Feedback from **Professor Marnim Galib** is being sought to refine the scope, with updates to follow.

---

## 🚀 Getting Started

> Detailed instructions will be added post-implementation.

```bash
# Clone the repository
git clone https://github.com/Akobabs/CardiacMotionXAI.git

# Install dependencies (to be specified in requirements.txt)
pip install -r requirements.txt

# Download and preprocess EchoNet-Dynamic subset (1000 videos)
# Run scripts for optical flow, CNN training, and Grad-CAM visualization

📜 License
This project is licensed under the MIT License (LICENSE). See the LICENSE file for details.

🙏 Acknowledgments
Supervisor: Professor Marnim Galib, for his supervision, guidance, and valuable feedback throughout the project.
Dataset: Stanford AIMI for providing the EchoNet-Dynamic dataset.
Tools: OpenCV, PyTorch, and Captum communities for their robust open-source libraries.

📬 Contact
Author: ADEMOLA, Akorede Adejare
Email: axa6715@mavs.uta.edu (mailto:axa6715@mavs.uta.edu)
GitHub: github.com/Akobabs