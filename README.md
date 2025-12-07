# Explainable Medical Image Classification

This repository contains explainable AI projects for medical image classification, covering brain tumor MRI scans and histopathology images for cancer detection. The goal across all projects is to achieve high classification accuracy while making the model’s decisions interpretable using modern XAI methods and attention.

---

## Projects Overview

### 1️⃣ Explainable Brain Tumor Classification (MRI) 🧠
**File:** `Explainable Brain Tumor Classification.ipynb`  
**Objective:** Detect and classify brain tumors from MRI scans with interpretable predictions.

**Key Features:**
- MRI-based tumor classification into different types.
- Explainability via CAM-based methods:
  - Grad-CAM 🌟
  - Grad-CAM++ ⚡
  - Score-CAM 🎯

**Highlights:**
- Clearly shows which regions influence model predictions.
- Useful for research, diagnostics, and exploring AI in healthcare.

---

### 2️⃣ Explainable AI for Cancer Detection in Histopathology 🔬
**File:** `ResNet50XAI.ipynb`  
**Objective:** Apply Grad-CAM to a ResNet-50 model for multi-class classification of histopathology images (cancerous vs. non-cancerous) to enhance interpretability.

**Key Features:**
- Deep CNN (ResNet-50) for high-accuracy detection.
- Grad-CAM overlays on tissue images to highlight influential regions.
- Supports model validation, error analysis, and discovery of potential biomarkers.

---

### 3️⃣ Breast Cancer Histopathological Image Classification (ResNet50) 🩺
**File:** `Breast-Cancer-Histopathology-Image-Classification.ipynb`  
**Objective:** Classify breast cancer histopathology images into Normal and Tumor classes with a robust deep learning pipeline.

**Pipeline Highlights:**
- Custom dataset class and preprocessing with data augmentation.
- ResNet50 model with modified final layer for binary classification.
- Training/validation/test split: 70% / 15% / 15%.
- Achieved ~98% test accuracy with balanced precision and recall.

**Additional Info:**
- Visualizations include loss/accuracy curves and confusion matrices.
- Training history and artifacts saved for traceability.

---

### 4️⃣ Cancer Detection using Attention-Based Network 🩺🔬
**File:** `Histopathologic Cancer Detection.ipynb`  
**Objective:** Enhance cancer detection in histopathology images using attention-based deep neural networks to improve accuracy and interpretability.

**Key Features:**
- Attention modules help the model focus on relevant tissue regions.
- Uses VGG16 architecture for feature extraction and classification.
- Provides visual explanations for clinical validation.
- Supports classification of breast cancer subtypes in tissue patches.

---

## Summary
This repository demonstrates the integration of **high-performing medical image classifiers** with **explainable AI techniques**, including Grad-CAM, Grad-CAM++, and attention mechanisms. These projects highlight both **diagnostic accuracy** and **interpretability**, making AI models more transparent and clinically useful.

---

💡 **Tip:** Explore each project in its respective folder (e.g., `BrainTumor`, `Histopathology_GradCAM`, `BreastCancer_ResNet50`, `Attention_Network`) to run experiments, visualize results, and understand how AI models make decisions in medical imaging.
