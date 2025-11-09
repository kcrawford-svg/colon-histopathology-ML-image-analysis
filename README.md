# Histopathology-Based Deep Feature Extraction and Exploratory Analysis for Colon Adenocarcinoma Detection


## Project Overview
This project performs preprocessing and exploratory analysis of the **Colon Cancer Histopathological Images** dataset. The dataset contains high-resolution microscope images of colon tissue labeled as **normal** or **adenocarcinoma (malignant)**.

**Goals:**  
- Explore image statistics (size, color channels, class distribution)  
- Visualize sample images  
- Preprocess images for machine learning (resize, recolor, flatten)  
- Apply dimensionality reduction (PCA, Randomized PCA)  
- Extract meaningful image features (e.g., DAISY descriptors)  
- Evaluate features for predictive modeling

**Prediction Task:**  
Binary classification:  
- `colon_n` → normal colon tissue  
- `colon_aca` → colon adenocarcinoma  

---

## Dataset
**Source:** [Kaggle – Lung & Colon Cancer Histopathological Images](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images)  

Please download the `colon_image_sets` folder and place it in `data/`.
