# Histopathology-Based Deep Feature Extraction and Exploratory Analysis for Colon Adenocarcinoma Detection


## Project Overview
This project performs exploratory data analysis, feature engineering, and baseline machine-learning preparation on a publicly available colon cancer histopathology image dataset. 

The goal is to identify discriminative image features that can separate benign colon tissue from adenocarcinoma tissue, using both traditional feature extraction (DAISY) and dimensionality reduction (PCA) as pre-deep-learning baselines.

**Goals:**  
- Perform statistical and visual analysis of histopathology images
- Preprocess high-resolution microscopy slides into ML-ready formats
- Engineer biologically-relevant texture & morphology features
- Compare PCA-based latent representations vs classical feature descriptors
- Build a baseline classifier for tumor vs normal tissue using engineered features
-	Prepare pipeline for future extension into deep learning (CNN, MIL, or ViT)
  

---

**Methods Implemented**

- Image preprocessing (resize, RGB normalization, flattening)
- Feature extraction using DAISY (Dense SIFT-like descriptor)
- Dimensionality reduction using PCA & randomized PCA
- Baseline classifier using engineered feature vectors
- Exploratory visualization (classwise PCA embedding plots, etc)

**Dataset Summary**

- Modality: Bright-field microscopy (H&E stained tissue)
- Resolution: High-resolution patches (color RGB)
- Classes: Normal colon epithelium (colon_n) vs adenocarcinoma (colon_aca)
- Task Type: Binary classification, patch-level




## Dataset Source
**Source:** [Kaggle – Lung & Colon Cancer Histopathological Images](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images)  


