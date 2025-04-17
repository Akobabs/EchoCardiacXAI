# 🫀 CardiacMotionXAI

*A computer vision system to detect abnormal cardiac motion in echocardiogram videos using optical flow, CNNs, and explainable AI (Grad-CAM).*

Developed for **CSE 6367: Computer Vision, Fall 2025** at the **University of Texas at Arlington**  
**Supervisor:** Professor Marnim Galib

---

## 📖 Overview

This repository hosts the planned implementation of a computer vision project focused on detecting abnormal cardiac motion in echocardiogram videos using the **EchoNet-Dynamic** dataset.

The system integrates:
- Optical flow for motion feature extraction
- CNNs for classification
- Grad-CAM for explainable predictions

🗓️ *Status:* Planning Phase (as of April 17, 2025)  
🧠 *Focus:* Interpretability and robust classification in medical diagnostics

---

## 🎯 Objectives

- **Primary Goal:** Classify echocardiogram videos as *normal* or *abnormal* based on cardiac motion patterns.
- **Explainability:** Visualize frames or regions influencing predictions using Grad-CAM.
- **Course Alignment:** Apply core techniques from CSE 6367 — optical flow, deep learning, and feature extraction.

---

## 📊 Dataset

**📁 EchoNet-Dynamic** – 10,030 annotated videos from Stanford AIMI.  
➡️ *Project Subset:* 1,000 videos (500 normal, 500 abnormal)

**Sources:**
- [EchoNet-Dynamic Dataset](https://echonet.github.io/dynamic/)
- [Papers With Code](https://paperswithcode.com/dataset/echonet-dynamic)

---

## 🛠️ Methodology

1. **Motion Feature Extraction**
   - Use optical flow to track cardiac motion across frames.

2. **Classification**
   - Fine-tune a pre-trained CNN (e.g., ResNet) to classify videos.

3. **Explainable AI**
   - Apply Grad-CAM to highlight decision-influencing regions.

4. **Evaluation**
   - Use accuracy, precision, recall, and F1-score.
   - Qualitative evaluation of Grad-CAM outputs.

---

## 🧰 Tools and Technologies

- **Language:** Python
- **Libraries:**
  - `OpenCV` – Optical flow
  - `PyTorch` – Deep learning
  - `Captum` – Model interpretability (Grad-CAM)
- **Environment:** Google Colab / Local GPU
- **Data Processing:** `pydicom` for DICOM-format echocardiograms

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

As of **April 17, 2025**, this project is in the **planning phase**.  
This repository serves as a **placeholder** for upcoming implementation during Fall 2025.  
Feedback from **Professor Marnim Galib** is being incorporated to refine the scope.

---

## 🚀 Getting Started (Planned)

> Steps to be added post-implementation.

```bash
# Clone the repository
git clone https://github.com/Akobabs/CardiacMotionXAI.git

# Install dependencies
# (requirements.txt to be created)

# Download and preprocess EchoNet-Dynamic subset (1000 videos)

# Run scripts for:
# - Optical flow extraction
# - CNN training
# - Grad-CAM visualization
---

## 📜 License
This project is licensed under the MIT License.
See the LICENSE file for more information.

---

## 🙏 Acknowledgments
Professor Marnim Galib – For supervision, guidance, and insights throughout the project.

Stanford AIMI – For providing the EchoNet-Dynamic dataset used in this research.

OpenCV, PyTorch, and Captum – For their powerful open-source libraries enabling rapid development of computer vision systems.

---
## 📬 Contact
Author: **ADEMOLA, Akorede Adejare**
📧 Email: axa6715@mavs.uta.edu
🔗 GitHub: github.com/Akobabs

---